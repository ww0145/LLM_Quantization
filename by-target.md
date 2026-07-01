# LLM Quantization by Target

<details open>
<summary><strong>Weight Quantization</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** |
| --- | --- | --- | :---: |
| [![arXiv](https://img.shields.io/badge/arXiv-2022-red)]()<br>[GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers](https://arxiv.org/abs/2210.17323)<br>Elias Frantar et al. | [![Area](https://img.shields.io/badge/Area-LLM-purple)]() [![Area](https://img.shields.io/badge/Area-Weight-purple)]() | [![Type](https://img.shields.io/badge/Type-PTQ-green)]() [![Type](https://img.shields.io/badge/Type-Hessian--Based-green)]() | [Paper](https://arxiv.org/abs/2210.17323)<br>[Code](https://github.com/IST-DASLab/gptq) |
| [![arXiv](https://img.shields.io/badge/arXiv-2023-red)]()<br>[AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration](https://arxiv.org/abs/2306.00978)<br>Ji Lin et al. | [![Area](https://img.shields.io/badge/Area-Weight-purple)]() [![Area](https://img.shields.io/badge/Area-Activation-purple)]() | [![Type](https://img.shields.io/badge/Type-W4A16-green)]() [![Type](https://img.shields.io/badge/Type-Activation--Aware-green)]() | [Paper](https://arxiv.org/abs/2306.00978)<br>[Code](https://github.com/mit-han-lab/llm-awq) |
| [![arXiv](https://img.shields.io/badge/arXiv-2023-red)]()<br>[SpQR: A Sparse-Quantized Representation for Near-Lossless LLM Weight Compression](https://arxiv.org/abs/2306.03078)<br>Tim Dettmers et al. | [![Area](https://img.shields.io/badge/Area-Weight-purple)]() | [![Type](https://img.shields.io/badge/Type-Sparse--Outlier-green)]() [![Type](https://img.shields.io/badge/Type-Low--Bit-green)]() | [Paper](https://arxiv.org/abs/2306.03078) |
| [![arXiv](https://img.shields.io/badge/arXiv-2023-red)]()<br>[SqueezeLLM: Dense-and-Sparse Quantization](https://arxiv.org/abs/2306.07629)<br>Sehoon Kim et al. | [![Area](https://img.shields.io/badge/Area-Weight-purple)]() [![Area](https://img.shields.io/badge/Area-Edge-purple)]() | [![Type](https://img.shields.io/badge/Type-Dense--Sparse-green)]() [![Type](https://img.shields.io/badge/Type-Low--Bit-green)]() | [Paper](https://arxiv.org/abs/2306.07629) |

</details>

<details open>
<summary><strong>Activation and Weight-Activation Quantization</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** |
| --- | --- | --- | :---: |
| [![arXiv](https://img.shields.io/badge/arXiv-2022-red)]()<br>[LLM.int8(): 8-bit Matrix Multiplication for Transformers at Scale](https://arxiv.org/abs/2208.07339)<br>Tim Dettmers et al. | [![Area](https://img.shields.io/badge/Area-LLM-purple)]() [![Area](https://img.shields.io/badge/Area-Activation-purple)]() | [![Type](https://img.shields.io/badge/Type-INT8-green)]() [![Type](https://img.shields.io/badge/Type-Outlier--Aware-green)]() | [Paper](https://arxiv.org/abs/2208.07339)<br>[Code](https://github.com/bitsandbytes-foundation/bitsandbytes) |
| [![arXiv](https://img.shields.io/badge/arXiv-2022-red)]()<br>[SmoothQuant: Accurate and Efficient Post-Training Quantization for Large Language Models](https://arxiv.org/abs/2211.10438)<br>Guangxuan Xiao et al. | [![Area](https://img.shields.io/badge/Area-LLM-purple)]() [![Area](https://img.shields.io/badge/Area-PTQ-purple)]() | [![Type](https://img.shields.io/badge/Type-W8A8-green)]() [![Type](https://img.shields.io/badge/Type-Smoothing-green)]() | [Paper](https://arxiv.org/abs/2211.10438)<br>[Code](https://github.com/mit-han-lab/smoothquant) |
| [![arXiv](https://img.shields.io/badge/arXiv-2023-red)]()<br>[OmniQuant: Omnidirectionally Calibrated Quantization for Large Language Models](https://arxiv.org/abs/2308.13137)<br>Wenqi Shao et al. | [![Area](https://img.shields.io/badge/Area-PTQ-purple)]() [![Area](https://img.shields.io/badge/Area-Weight--Activation-purple)]() | [![Type](https://img.shields.io/badge/Type-Calibration-green)]() [![Type](https://img.shields.io/badge/Type-Learnable--Clipping-green)]() | [Paper](https://arxiv.org/abs/2308.13137)<br>[Code](https://github.com/OpenGVLab/OmniQuant) |

</details>

<details open>
<summary><strong>KV Cache, Attention, Embedding, Optimizer, and Gradient Quantization</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** |
| --- | --- | --- | :---: |
| [![arXiv](https://img.shields.io/badge/arXiv-2024-red)]()<br>[KIVI: A Tuning-Free Asymmetric 2bit Quantization for KV Cache](https://arxiv.org/abs/2402.02750)<br>Zirui Liu et al. | [![Area](https://img.shields.io/badge/Area-KV--Cache-purple)]() [![Area](https://img.shields.io/badge/Area-Long--Context-purple)]() | [![Type](https://img.shields.io/badge/Type-2--bit-green)]() [![Type](https://img.shields.io/badge/Type-Asymmetric-green)]() | [Paper](https://arxiv.org/abs/2402.02750) |
| [![arXiv](https://img.shields.io/badge/arXiv-2024-red)]()<br>[KVQuant: Towards 10 Million Context Length LLM Inference with KV Cache Quantization](https://arxiv.org/abs/2401.18079)<br>Coleman Hooper et al. | [![Area](https://img.shields.io/badge/Area-KV--Cache-purple)]() [![Area](https://img.shields.io/badge/Area-Long--Context-purple)]() | [![Type](https://img.shields.io/badge/Type-Serving-green)]() [![Type](https://img.shields.io/badge/Type-Low--Bit-green)]() | [Paper](https://arxiv.org/abs/2401.18079) |
| [![arXiv](https://img.shields.io/badge/arXiv-2024-red)]()<br>[GEAR: An Efficient KV Cache Compression Recipe for Near-Lossless Generative Inference of LLM](https://arxiv.org/abs/2403.05527)<br>Hao Kang et al. | [![Area](https://img.shields.io/badge/Area-KV--Cache-purple)]() [![Area](https://img.shields.io/badge/Area-Serving-purple)]() | [![Type](https://img.shields.io/badge/Type-Compression-green)]() [![Type](https://img.shields.io/badge/Type-Low--Rank-green)]() | [Paper](https://arxiv.org/abs/2403.05527) |
| [![arXiv](https://img.shields.io/badge/arXiv-2023-red)]()<br>[FP8-LM: Training FP8 Large Language Models](https://arxiv.org/abs/2310.18313)<br>Houwen Peng et al. | [![Area](https://img.shields.io/badge/Area-Training-purple)]() [![Area](https://img.shields.io/badge/Area-Number--Format-purple)]() | [![Type](https://img.shields.io/badge/Type-FP8-green)]() [![Type](https://img.shields.io/badge/Type-Low--Precision-green)]() | [Paper](https://arxiv.org/abs/2310.18313) |

</details>
