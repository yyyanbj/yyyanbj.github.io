---
title: "Im2col-Winograd: An Efficient and Flexible Fused-Winograd Convolution for NHWC Format on GPUs"
date: 2024-08-12 00:01:00 +0800
selected: false
pub: "ICPP'24, CCF-B"
pub_last: ' <span class="badge badge-pill badge-publication badge-danger">Oral</span>'
pub_date: "(2024)"
abstract: >-
  Im2col-Winograd decomposes multidimensional convolution into 1D Winograd operations to accelerate NHWC-format convolution on GPUs with less workspace. The implementation supports filter widths 2–9 and reports speedups over cuDNN baselines.
# cover: /assets/images/covers/im2col.png
authors:
  - Zhiyi ZHANG
  - Pengfei ZHANG
  - Zhuopin XU
  - Bingjie YAN
  - Qi WANG†
links:
  Paper: https://dl.acm.org/doi/10.1145/3673038.3673039
  Bib: bib/zhang2024im2col.txt
---
