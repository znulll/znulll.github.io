---
title: Neural Collaborative Filtering (2017)
author: Junho Kim
date: 2020-10-24 00:10:30 +0800
categories: [Paper_review, rec_sys]
tags: [Recommendation, Deep Learning]
math: true
---

## Link
- paper: <https://arxiv.org/pdf/1205.2618.pdf>
- code : <https://github.com/hexiangnan/neural_collaborative_filtering>

---

## Summary
> 목표: Implicit feedback 기반의 item 추천
> 방법: NCF Framework = Generalized Matrix Factorization + Multi-Layer Perceptron
> 결과: Outperform than BPR, eALS, KNN, ...

---

## Abstract
- 최근 DNN은 다양한 분야에서 큰 성공을 거뒀지만, 추천 시스템 분야에서의 DNN 시도는 상대적으로 적음
- 기존의 MF의 inner product를 neural architecture로 대체하는 NCF 프레임워크를 제시함
-

---

## 1. Introduction

---

## 2. Preliminaries

### 2.1. Learning from implicit data

### 2.2. Matrix Factorization

---

## 3. Neural collaborative Filtering

### 3.1. General Framework

### 3.2. Generalized matrix factoriazation (GMF)

### 3.3. Multi-layer Perceptron

### 3.4. Fusion of GMF and MLP

---

## 4. Experiments

### 4.1. Experimental settings

### 4.2. RQ1: Performance comparison

#### 4.2.1. Utility of pre-training

### 4.3. RQ2: Log loss with negative sampling

### 4.4. RQ3: Is deep learning helpful?

---

## 5. Related work

---

## 6. Conclusion and future work




## Reverse Footnote

[^footnote]: The footnote source.
