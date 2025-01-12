---
title: "MetPurity: A Learning-Based Tool of Pure Method Identification
for Automatic Test Generation"
collection: publications
permalink: /publication/ase-20
excerpt: '![](https://yu-runze.github.io/files/ASE/structure.png) In object-oriented programming, a method is pure if calling the
method does not change object states that exist in the pre-states
of the method call. Pure methods are widely-used in automatic
techniques, including test generation, compiler optimization, and
program repair. Due to the source code dependency, it is infeasible
to completely and accurately identify all pure methods. Instead,
existing techniques such as ReImInfer are designed to identify a
subset of accurate results of pure method and mark the other methods as unknown ones. In this paper, we designed and implemented
**MetPurity, a learning-based tool of pure method identification.**
Given all methods in a project, MetPurity labels a training set via
automatic program analysis and builds a binary classifier (implemented with the random forest classifier) based on the training set.
This classifier is used to predict the purity of all the other methods
(i.e., unknown ones) in the same project. Preliminary evaluation on
four open-source Java projects shows that MetPurity can provide a
list of identified pure methods with a low error rate. Applying MetPurity to EvoSuite can increase the number of generated assertions
for regression testing in test generation by EvoSuite.'
date: 2020-07-02
venue: 'Proceedings of the International Conference on Automated Software Engineering (ASE 2020)'
---

## Abstract
In object-oriented programming, a method is pure if calling the
method does not change object states that exist in the pre-states
of the method call. Pure methods are widely-used in automatic
techniques, including test generation, compiler optimization, and
program repair. Due to the source code dependency, it is infeasible
to completely and accurately identify all pure methods. Instead,
existing techniques such as ReImInfer are designed to identify a
subset of accurate results of pure method and mark the other methods as unknown ones. In this paper, we designed and implemented MetPurity, a learning-based tool of pure method identification.Given all methods in a project, MetPurity labels a training set via
automatic program analysis and builds a binary classifier (implemented with the random forest classifier) based on the training set.
This classifier is used to predict the purity of all the other methods
(i.e., unknown ones) in the same project. Preliminary evaluation on
four open-source Java projects shows that MetPurity can provide a
list of identified pure methods with a low error rate. Applying MetPurity to EvoSuite can increase the number of generated assertions
for regression testing in test generation by EvoSuite.