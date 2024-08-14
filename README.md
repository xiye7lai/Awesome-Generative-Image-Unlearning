# Awesome-Generative-Image-Unlearning

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![GitHub stars](https://img.shields.io/github/stars/xiye7lai/Awesome-Generative-Image-Unlearning?color=yellow&label=Stars)

A collection of academic articles, published methodology, datasets and benchmarks on the subject of **machine unlearning for generative image models**.

- [Awesome-Generative-Image-Unlearning](#awesome-generative-image-unlearning)
  - [Surveys](#surveys)
  - [T2I-Unlearning](#text-to-image-model-unlearning)
  - [I2I-Unlearning](#image-to-image-model-unlearning)
  - [GAN-Unlearning](#gan-unlearning)
  - [Datasets and Benchmarks](#datasets-and-benchmarks)
  
----------

## Surveys
| **Paper** | **Venue** | **Year** | 
| --------------- | ---- | ---- | 
| [Machine Unlearning in Generative AI: A Survey](https://arxiv.org/abs/2407.20516) | _arXiv_ | 2024 |
----------

## Text-to-Image Model Unlearning
| **Paper** | **Year** | **Venue** | **Code** | **Type** |
| --------------- | :----: | ---- | :----: | :----: |
| [Espresso: Robust Concept Filtering in Text-to-Image Models](https://arxiv.org/abs/2404.19227) | 2024 | _arXiv_ | - | Concept Unlearning |
| [MACE: Mass Concept Erasure in Diffusion Models](https://arxiv.org/abs/2403.06135) | 2024 | _CVPR'24_ | [Code](https://github.com/Shilin-LU/MACE) | Concept Unlearning |
| [Probing Unlearned Diffusion Models: A Transferable Adversarial Attack Perspective](https://arxiv.org/abs/2404.19382) | 2024 |   _arXiv_   | [Code](https://github.com/hxxdtd/PUND) | Attack |
| [ConceptPrune: Concept Editing in Diffusion Models via Skilled Neuron Pruning](https://arxiv.org/abs/2405.19237) | 2024 | _arXiv_ | - | Concept Unlearning |
| [Pruning for Robust Concept Erasing in Diffusion Models](https://arxiv.org/abs/2405.16534) | 2024 | _arXiv_ | - | Concept Unlearning |
| [R.A.C.E.: Robust Adversarial Concept Erasure for Secure Text-to-Image Diffusion Model](https://arxiv.org/abs/2405.16341) | 2024 | _arXiv_ | - | Concept Unlearning |
| [Defensive Unlearning with Adversarial Training for Robust Concept Erasure in Diffusion Models](https://arxiv.org/abs/2405.15234) | 2024 | _arXiv_ | [Code](https://github.com/OPTML-Group/AdvUnlearn) | Concept Unlearning |
| [Unlearning Concepts in Diffusion Model via Concept Domain Correction and Concept Preserving Gradient](https://arxiv.org/abs/2405.15304) | 2024 | _arXiv_ | - | Concept Unlearning |
| [SafeGen: Mitigating Unsafe Content Generation in Text-to-Image Models](https://arxiv.org/abs/2404.06666) | 2024 | _arXiv_ | - | Concept Unlearning |
| [Robust Concept Erasure Using Task Vectors](https://arxiv.org/abs/2404.03631) | 2024 | _arXiv_ | - | Concept Unlearning |
| [Unveiling and Mitigating Memorization in Text-to-image Diffusion Models through Cross Attention](https://arxiv.org/abs/2403.11052) | 2024 | _arXiv_ | [Code](https://github.com/renjie3/MemAttn) | - |
| [Separable Multi-Concept Erasure from Diffusion Models](https://arxiv.org/abs/2402.05947) | 2024 | _arXiv_ | [Code](https://github.com/Dlut-lab-zmn/SepCE4MU) | Concept Unlearning |
| [EraseDiff: Erasing Data Influence in Diffusion Models](https://arxiv.org/abs/2401.05779) | 2024 | _arXiv_ | - | Concept Unlearning |
| [One-Dimensional Adapter to Rule Them All: Concepts, Diffusion Models and Erasing Applications](https://arxiv.org/abs/2312.16145) | 2024 | _CVPR'24_ | [Code](https://github.com/Con6924/SPM) | Concept Unlearning |
| [All but One: Surgical Concept Erasing with Model Preservation in Text-to-Image Diffusion Models](https://arxiv.org/abs/2312.12807) | 2023 | _AAAI'24_ | - | Concept Unlearning |
| [Circumventing Concept Erasure Methods For Text-to-Image Generative Models](https://arxiv.org/abs/2308.01508) | 2023 | _ICLR'24_ | [Code](https://github.com/NYU-DICE-Lab/circumventing-concept-erasure) | Attack |
| [Ring-A-Bell! How Reliable are Concept Removal Methods for Diffusion Models?](https://arxiv.org/abs/2310.10012) | 2023 | _ICLR'24_ | [Code](https://github.com/chiayi-hsu/Ring-A-Bell) |  Attack   |
| [To Generate or Not? Safety-Driven Unlearned Diffusion Models Are Still Easy To Generate Unsafe Images ... For Now](https://arxiv.org/abs/2310.11868) | 2023 | _ECCV'24_ | [Code](https://github.com/OPTML-Group/Diffusion-MU-Attack) | Attack |
| [SalUn: Empowering Machine Unlearning via Gradient-based Weight Saliency in Both Image Classification and Generation](https://arxiv.org/abs/2310.12508) | 2023 | _ICLR'24_ | [Code](https://github.com/OPTML-Group/Unlearn-Saliency) | Concept Unlearning |
| [Selective Amnesia: A Continual Learning Approach to Forgetting in Deep Generative Models](https://arxiv.org/abs/2305.10120) | 2023 | _NeurIPS'23_ | [Code](https://github.com/clear-nus/selective-amnesia) | Concept Unlearning |
| [Ablating Concepts in Text-to-Image Diffusion Models](https://arxiv.org/abs/2303.13516) | 2023 | _ICCV'23_ | [Code](https://github.com/nupurkmr9/concept-ablation) | Concept Unlearning |
| [Erasing Concepts from Diffusion Models](https://arxiv.org/abs/2303.07345) | 2023 | _ICCV'23_ | [Code](https://github.com/rohitgandikota/erasing) | Concept Unlearning |
| [Degeneration-Tuning: Using Scrambled Grid shield Unwanted Concepts from Stable Diffusion](https://arxiv.org/abs/2308.02552) | 2023 | _ACM MM'23_ | - | Concept Unlearning |
| [Receler: Reliable Concept Erasing of Text-to-Image Diffusion Models via Lightweight Erasers](https://arxiv.org/abs/2311.17717) | 2023 | _arXiv_ | - | Concept Unlearning |
| [Implicit Concept Removal of Diffusion Models](https://arxiv.org/abs/2310.05873) | 2023 | _arXiv_ | - | Concept Unlearning |
| [Forget-Me-Not: Learning to Forget in Text-to-Image Diffusion Models](https://arxiv.org/abs/2303.17591) | 2023 | _arXiv_ | [Code](https://github.com/SHI-Labs/Forget-Me-Not) | Concept Unlearning |
----------

## Image-to-Image Model Unlearning
| **Paper** | **Year** | **Venue** | **Code** | **Type** |
| --------------- | :----: | ---- | :----: | :----: |
| [Generative Unlearning for Any Identity](https://arxiv.org/abs/2405.09879) | 2024 | _CVPR'24_ | [[Code]](https://github.com/KHU-AGI/GUIDE) | Identity Unlearning |
| [Machine Unlearning for Image-to-Image Generative Models](https://arxiv.org/abs/2402.00351) | 2024 | _ICLR'24_ | [[Code]](https://github.com/jpmorganchase/l2l-generator-unlearning) | Sample Unlearning, Class Unlearning |
----------

## GAN Unlearning
| **Paper** | **Year** | **Venue** | **Code** | **Type** |
| --------------- | :----: | ---- | :----: | :----: |
| [FAST: Feature Aware Similarity Thresholding for Weak Unlearning in Black-Box Generative Models](https://arxiv.org/abs/2312.14895) | 2024 | _arXiv_ | - | Class Unlearning, Feature Unlearning |
| [Adapt then Unlearn: Exploiting Parameter Space Semantics for Unlearning in Generative Adversarial Networks](https://arxiv.org/abs/2309.14054) | 2023 | _arXiv_ | - | Feature Unlearning |
| [Generative Adversarial Networks Unlearning](https://arxiv.org/abs/2308.09881) | 2023 | _arXiv_ | - | Sample Unlearning, Class Unlearning |
| [Feature Unlearning for Pre-trained GANs and VAEs](https://arxiv.org/abs/2303.05699) | 2023 | _arXiv_ | - | Feature Unlearning |
----------

## Datasets and Benchmarks
| **Paper** | **Year** | **Venue** | **Website** | **Type** |
| --------------- | :----: | ---- | :----: | :----: |
| [UnlearnCanvas: A Stylized Image Dataset to Benchmark Machine Unlearning for Diffusion Models](https://arxiv.org/abs/2402.11846) | 2024 | _arXiv_ | [[Website]](https://unlearn-canvas.netlify.app/) | Style Transfer, Concept Unlearning, etc. |

----------

![visitors](https://visitor-badge.laobi.icu/badge?page_id=xiye7lai.Awesome-Generative-Image-Unlearning)

