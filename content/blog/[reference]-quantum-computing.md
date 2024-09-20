---
title: [reference] Quantum computing
date: 2024-09-20T14:29:29.383Z
---

- [Count-Free Single-Photon 3D Imaging with Race Logic](https://ieeexplore-ieee-org.proxy.lib.utc.edu/abstract/document/10210115)
    -  Abstract:
>Single-photon cameras (SPCs) have emerged as a promising new technology for high-resolution 3D imaging. A single-photon 3D camera determines the round-trip time of a laser pulse by precisely capturing the arrival of individual photons at each camera pixel. Constructing photon-timestamp histograms is a fundamental operation for a single-photon 3D camera. However, in-pixel histogram processing is computationally expensive and requires large amount of memory per pixel. Digitizing and transferring photon timestamps to an off-sensor histogramming module is bandwidth and power hungry. Can we estimate distances without explicitly storing photon counts? Yes-here we present an online approach for distance estimation suitable for resource-constrained settings with limited bandwidth, memory and compute. The two key ingredients of our approach are (a) processing photon streams using race logic, which maintains photon data in the time-delay domain, and (b) constructing count-free equi-depth histograms as opposed to conventional equi-width histograms. Equi-depth histograms are a more succinct representation for “peaky” distributions, such as those obtained by an SPC pixel from a laser pulse reflected by a surface. Our approach uses a binner element that converges on the median (or, more generally, to another k-quantile) of a distribution. We cascade multiple binners to form an equi-depth histogrammer that produces multi-bin histograms. Our evaluation shows that this method can provide at least an order of magnitude reduction in bandwidth and power consumption while maintaining similar distance reconstruction accuracy as conventional histogram-based processing methods.


