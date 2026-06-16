# KT-CATS

This repository is the official implementation of the paper: **"KT-CATS: Multi-Agent Collaboration with Bounded Memory for Continuous Clinical Reasoning"**.

---

## 📢 Note on Code & Data Availability

> **Important:** To protect the intellectual property of this research during the peer-review process, the complete codebase is currently maintained in a private development branch. **All resources (including source code and configuration files) will be made fully open-source and publicly released here immediately upon the formal acceptance/publication of our manuscript.**

---

## 📊 Dataset Acquisition and Setup

Due to licensing and copyright regulations, we do *not* host or redistribute any raw third-party datasets in this repository. To replicate the benchmarks used in our study, please acquire the raw data directly from their official sources:

1. **Dataset A & B (TCM Licensure & Attending Exams)**:
   - Sourced from the Multi-Task Benchmark Framework for TCM (**MTCMB**).
   - Official Repository: [MTCMB on GitHub](https://github.com/Wayyuanyuan/MTCMB)
   - Citation: Kong, S., et al., 2025. MTCMB: A multi-task benchmark framework for evaluating LLMs on knowledge, reasoning, and safety in Traditional
Chinese Medicine. arXiv:2506.01252. preprint at https://arxiv.org/abs/2506.01252.

2. **Dataset C (TCMLE Practice Questions)**:
   - Sourced from the open-source repository on Hugging Face.
   - Official Repository: [Traditional-Chinese-Medicine-Exam on Hugging Face](https://huggingface.co/datasets/SylvanL/Traditional-Chinese-Medicine-Exam)
   

---

## 📂 Projected Repository Structure

Upon the paper's acceptance, the repository will be populated with the following codebase structure to ensure seamless reproducibility:

```text
KT-CATS/
├── src/                         # Source Code Directory
│   ├── agent.py                 # Contextual Thompson Sampling agent logic
│   ├── experts.py               # LLM expert agent initialization & API wrappers
│   ├── utils.py                 # Text preprocessing & semantic embedding utilities
│   └── main.py                  # Main training & execution loop
│
├── requirements.txt             # Python dependencies
└── README.md                    # This file

---

## 🛠️ System Requirements (Preview)
The codebase requires Python 3.8+ and the following primary libraries:
- torch >= 2.0
- pandas
- numpy
- sentence-transformers
- openai
- scipy
- matplotlib & seaborn
Detailed installation instructions and configuration steps will be updated upon release.
