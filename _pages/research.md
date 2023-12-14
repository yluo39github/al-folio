---
layout: page
title: Research
permalink: /projects/
description: My research path began with hardware security primitives and progressed to the system level. FPGA Virtualization is a key aspect of many of my Ph.D. research projects. My current research direction will focus more on the contribution of hardware systems to security and privacy, and continuously explore truly valuable cloud computing systems from hardware, system, and software levels.
nav: false
nav_order: 2
horizontal: false
---

1. [FPGA Virtualization System](#FPGA_Vir)
2. [Hardware Security](#Hw_sec)
3. [Trustworthy AI Acceleration and Optimization](#ai)

1. [Encrypted databases](#dbms)
2. [Private distributed ledgers/ blockchains](#blockchain)
3. [Secure and Trustworthy AI/ML systems](#ai)

## FPGA Virtualization System: Hardware-Oriented Threats and Mitigations <a name="FPGA_Vir"></a>
Technologies for cloud virtualization are extensively utilized in public cloud services, with a significant focus in both industry and academic research currently on virtualization technologies involving FPGA-based cloud instances.

Our vision is to develop a commercial prototype of a Virtualized FPGA, further enhancing hardware acceleration support for internet applications. Considering the distinct system architecture of cloud FPGA instances, as opposed to traditional CPU/GPU-based cloud instances, and the hardware programmability of FPGAs, our focus begins with the security challenges of multi-tenant FPGAs. We explore potential attack models and specific, commonly used attack methods, such as those in AI inference applications, to generate ideas for the design of Cloud FPGA hypervisors.




A persistent issue in today's society is that organizations handling private or sensitive data, i.e. health records, banking transactions, defense industry and military data etc, strive to engage in collaborative data analysis, but they are restricted from sharing it. 

Our aspiration is to architect pragmatic data systems to facilitate the practice of collaborative analytics over confidential data. To accomplish this aim, we delve into the synergistic relationship among **differential privacy**, **cryptography**, and **trusted hardwares** by establishing innovative algorithms and system designs that articulate the interconnection between these spheres, taking into account both theoretical perspectives and pragmatic approaches to systems building.

##### **Featured publications**
###### Two-party computing (2PC) system 

- [AQ2PNN: Enabling Two-party Privacy-Preserving Deep Neural Network Inference with Adaptive Quantization](https://microarch.org/micro56/program/index.php) (**MICRO**), 2023


- [IncShrink: Architecting Efficient Outsourced Databases using Incremental MPC and Differential Privacy](https://arxiv.org/abs/2203.05084)  (**SIGMOD**), 2022
- [DP-Sync: Hiding Update Patterns in Secure Outsourced Databases with Differential Privacy](https://arxiv.org/abs/2103.15942) (**SIGMOD**), 2021
- [Crypt$\epsilon$:Crypto-Assisted Differential Privacy on Untrusted Servers](https://dl.acm.org/doi/10.1145/3318464.3380596) (**SIGMOD**), 2020

<br>


## Secure and Trustworthy AI/ML systems <a name="ai"></a>

My current research focuses on novel algorithms and hardware co-design for accelerating privacy-preserving machine learning, aiming to facilitate the practical deployment of PPML across various industries that interact with sensitive data, such as healthcare, biomedicine, banking, finance, etc.

##### **Featured publications**
- [LinGCN: Structural Linearized Graph Convolutional Network for Homomorphically Encrypted Inference](#) (**NeurIPS**), 2023
- [AQ2PNN: Enabling Two-party Privacy-Preserving Deep Neural Network Inference with Adaptive Quantization](#)(**MICRO**), 2023
- [AutoReP: Automatic ReLU Replacement for Fast Private Network Inference](#) (**ICCV**), 2023

<br>

## Private distributed ledgers/ blockchains <a name="blockchain"></a>

The *permissionless* nature is widely recognized as a key innovation in modern blockchain technologies. However, this inherently open arrangement inevitably raises numerous privacy issues, for instance, everyone can observe each other's transactions. To mitigate these issues, **private blockchains** like Zcash have been proposed. These blockchains conceal transaction details using **cryptographic primitives** and employ **zero-knowledge proofs** to validate transactions, thereby preserving blockchain functionality.

My interests in this area primarily include: (i)Fundamentally understand the privacy implications of existing private blockchains; (ii) Explore principled techniques for designing efficient and robust private blockchains.

##### **Featured publications**
- [Private Proof-of-Stake Blockchains using Differentially-Private Stake Distortion](https://eprint.iacr.org/2023/787) (**Security**), 2023

**Check out our latest posts on Decentralized Thoughts, [part1](https://decentralizedthoughts.github.io/2023-07-21-ppos1/), [part2](https://decentralizedthoughts.github.io/2023-07-21-ppos2/), and our talks on [Zcon4](https://www.youtube.com/live/DMiw7m2Ku78?feature=share&t=9316) and [CESC23](https://www.youtube.com/watch?t=6635&v=q9-xxy43BnM&feature=youtu.be)**

<br>