---
permalink: /software/
title: ""
---

I develop scalable research software accompanying my work in active learning, Bayesian inference, and large-scale density-based clustering.
 
---

## Approx-FIRAL

Scalable active learning for multinomial logistic regression.

- Matrix-free Hessian operations
- Randomized trace estimation
- Preconditioned conjugate gradients
- Multi-GPU acceleration using MPI and CUDA
- Demonstrated scalability to million-point datasets

Related publication: SC 2024 (**Best Student Paper Finalist**)  
[Paper](https://arxiv.org/abs/2409.07392) · 
[Zenodo Repository](https://zenodo.org/records/13308577)

---

## kNN-DBSCAN

High-dimensional density-based clustering with distributed scalability.

- k-nearest-neighbor graph reformulation of DBSCAN
- Approximate distributed minimum spanning tree
- Hybrid MPI/OpenMP implementation
- Billion-point scalability experiments

Related publication: ACM TOPC 2025  
[Paper](https://arxiv.org/abs/2009.04552) · 
[GitHub Repository](https://github.com/ut-padas/knndbscan)