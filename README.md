# Awesome On-Policy Distillation

A curated list of research papers on on-policy distillation for large language models and reinforcement learning.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## 📚 Table of Contents

- [What is On-Policy Distillation?](#what-is-on-policy-distillation)
- [Papers](#papers)
  - [2026](#2026)
- [Contributing](#contributing)

## What is On-Policy Distillation?

On-policy distillation is a technique that transfers knowledge from a teacher model to a student model using data sampled from the student's own policy distribution. Unlike traditional off-policy distillation, this approach ensures better alignment between the training distribution and the deployment distribution, leading to more effective knowledge transfer.

## Papers

### 2026

#### **Video-OPD: Efficient Post-Training of Multimodal Large Language Models for Temporal Video Grounding via On-Policy Distillation**
- **Authors:** Jiaze Li, Hao Yin, Haoran Xu, Boshen Xu, Wenhui Tan, Zewen He, Jianzhong Ju, Zhenbo Luo, Jian Luan
- **Date:** February 2, 2026
- **arXiv:** [2402.xxxxx](https://arxiv.org/search/?query=Video-OPD)
- **Abstract:** Reinforcement learning has emerged as a principled post-training paradigm for Temporal Video Grounding (TVG) due to its on-policy optimization, yet existing GRPO-based methods remain fundamentally constrained by sparse reward signals and substantial computational overhead. We propose Video-OPD, an efficient post-training framework for TVG inspired by recent advances in on-policy distillation.

---

#### **OVD: On-policy Verbal Distillation**
- **Authors:** Jing Xiong, Hui Shen, Shansan Gong, Yuxin Cheng, Jianghan Shen, Chaofan Tao, Haochen Tan, Haoli Bai, Lifeng Shang, Ngai Wong
- **Date:** January 29, 2026
- **arXiv:** [2401.xxxxx](https://arxiv.org/search/?query=On-policy+Verbal+Distillation)
- **Abstract:** Knowledge distillation improves large language model (LLM) reasoning by compressing the knowledge of a teacher LLM to train smaller LLMs. On-policy distillation offers a promising approach to transfer reasoning capabilities from large teacher models to efficient student models.

---

#### **Self-Distilled Reasoner: On-Policy Self-Distillation for Large Language Models**
- **Authors:** Siyan Zhao, Zhihui Xie, Mengchen Liu, Jing Huang, Guan Pang, Feiyu Chen, Aditya Grover
- **Date:** January 26, 2026
- **arXiv:** [2401.xxxxx](https://arxiv.org/search/?query=Self-Distilled+Reasoner)
- **Abstract:** Knowledge distillation improves large language model (LLM) reasoning by compressing the knowledge of a teacher LLM to train smaller LLMs. On-policy knowledge distillation provides an effective framework for improving reasoning capabilities.

---

#### **Positive-Unlabeled Reinforcement Learning Distillation for On-Premise Small Models**
- **Authors:** Zhiqiang Kou, Junyang Chen, Xin-Qiang Cai, Xiaobo Xia, Ming-Kun Xie, Dong-Dong Wu, Biao Liu, Yuheng Jia, Xin Geng, Masashi Sugiyama, Tat-Seng Chua
- **Date:** January 28, 2026
- **arXiv:** [2401.xxxxx](https://arxiv.org/search/?query=Positive-Unlabeled+Reinforcement+Learning+Distillation)
- **Abstract:** We propose a positive-unlabeled (PU) RL distillation method for on-premise small-model deployment. Without human-labeled preferences or a reward model, our method enables efficient knowledge transfer.

---

#### **Continual Policy Distillation from Distributed Reinforcement Learning Teachers**
- **Authors:** Yuxuan Li, Qijun He, Mingqi Yuan, Wen-Tse Chen, Jeff Schneider, Jiayu Chen
- **Date:** January 29, 2026
- **arXiv:** [2401.xxxxx](https://arxiv.org/search/?query=Continual+Policy+Distillation)
- **Abstract:** We propose a novel teacher-student framework that decouples continual reinforcement learning (CRL) into two independent processes: training single-task teacher models through distributed RL and continually distilling them into a central generalist model.

---

#### **Reinforcement Learning via Self-Distillation**
- **Authors:** Jonas Hübotter, Frederike Lübeck, Lejs Behric, Anton Baumann, Marco Bagatella, Daniel Marta, Ido Hakimi, Idan Shenfeld, Thomas Kleine Buening, Carlos Guestrin, Andreas Krause
- **Date:** January 28, 2026
- **arXiv:** [2401.xxxxx](https://arxiv.org/search/?query=Reinforcement+Learning+via+Self-Distillation)
- **Abstract:** We formalize reinforcement learning with rich feedback and introduce Self-Distillation, a method that leverages detailed feedback signals to improve policy learning.

---

#### **KEPO: Knowledge-Enhanced Preference Optimization for Reinforcement Learning with Reasoning**
- **Authors:** Fan Yang, Rui Meng, Trudi Di Qi, Ali Ezzati, Yuxin Wen
- **Date:** January 30, 2026
- **arXiv:** [2401.xxxxx](https://arxiv.org/search/?query=KEPO+Knowledge-Enhanced+Preference)
- **Abstract:** Post-training remains fundamentally challenging due to sparse trajectory-level rewards, leading to ambiguous credit assignment and severe exploration failures. Recent on-policy optimization methods show promise in addressing these challenges.

---

#### **DISPO: Enhancing Training Efficiency and Stability in Reinforcement Learning for Large Language Model Mathematical Reasoning**
- **Authors:** Batuhan K. Karaman, Aditya Rawal, Suhaila Shakiah, Mohammad Ghavamzadeh, Mingyi Hong, Arijit Biswas, Ruida Zhou
- **Date:** January 31, 2026
- **arXiv:** [2401.xxxxx](https://arxiv.org/search/?query=DISPO+Reinforcement+Learning)
- **Abstract:** The domain presents a clear trade-off: PPO-style methods (e.g., GRPO/DAPO) offer training stability but exhibit slow learning trajectories due to their trust-region constraints on policy updates, while REINFORCE-style approaches demonstrate improved learning efficiency.

---

#### **Typhoon-S: Minimal Open Post-Training for Sovereign Large Language Models**
- **Authors:** Kunat Pipatanakul, Pittawat Taveekitworachai
- **Date:** January 25, 2026
- **arXiv:** [2401.xxxxx](https://arxiv.org/search/?query=Typhoon-S+Minimal+Open+Post-Training)
- **Abstract:** We present Typhoon S, a minimal and open post-training recipe that combines supervised fine-tuning, on-policy distillation, and small-scale reinforcement fine-tuning (RFT). Using Thai as a representative case study, we demonstrate effective knowledge transfer.

---

## Related Topics

- **Group Relative Policy Optimization (GRPO)**: Many on-policy distillation methods build upon GRPO principles
- **Policy Gradient Methods**: Foundation for many on-policy approaches
- **Knowledge Distillation**: Traditional distillation methods that on-policy variants improve upon
- **Reinforcement Learning from Human Feedback (RLHF)**: Related post-training paradigm

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For adding new papers, please follow this format:

```markdown
#### **Paper Title**
- **Authors:** Author names
- **Date:** Publication date
- **arXiv:** [arxiv_id](link)
- **Abstract:** Brief description
```

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released into the public domain.
