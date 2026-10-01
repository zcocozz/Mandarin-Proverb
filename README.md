# Benchmarking Large Language Models on Mandarin Proverb Explanation and Contextual Matching

This repository contains the data and appendix for the paper presented at LaTeLL 2026.

## About this Repository

This repository includes the following resources:

*   **Mandarin Proverb:** The dataset contains 1,152 Chinese proverbs. This is the subset of a larger dataset WISDOM
*   **Appendix:** The complete appendix for this study.

## Appendix

This section provides supplementary materials for the paper.

### A. Dataset Construction
The Mandarin dataset used in this study is a subset of the WISDOM dataset.

### B. Prompts
The prompts used in the experiments were written in Simplified Chinese. For readability, we translated them into English. See Appendix B for detailed prompts.

### C. Human Evaluation Guideline
See Appendix C for detailed guideline.

### D. Confidence Intervals for Human Evaluation
See Appendix D for confidence intervals for human evaluation results.

## Citation
Note: to be updated with the WISDOM dataset.

If you find our work helpful, please cite our paper :)!
```bibtex
@InProceedings{zhao-EtAl:2026:latell,
  author    = {Zhao, Xiaojing  and  Lamsiyah, Salima  and  Chersoni, Emmanuele  and  Xu, Han},
  title     = {Benchmarking Large Language Models on Mandarin Proverb Explanation and Contextual Matching},
  booktitle      = {Proceedings of the First International Conference on Language Technologies for Low-resource Languages (LaTeLL 2026)},
  month          = {September},
  year           = {2026},
  address        = {Fes, Morocco},
  publisher      = {Association for Computational Linguistics},
  pages     = {150--160},
  abstract  = {Mandarin proverbs condense historical allusions, figurative imagery, and conventionalized pragmatic functions into short expressions, making them a challenging test of culturally grounded language understanding. We evaluate four large language models (LLMs) on the Mandarin subset of the WISDOM dataset through two complementary tasks under zero-shot and few-shot prompting: situation-to-proverb selection, assessed by accuracy, and bilingual proverb explanation, assessed with automatic metrics and human judgments of semantic correctness, cultural faithfulness, clarity, and learner usefulness. The results reveal a clear gap between recognition and explanation. Models achieve high selection accuracy, with GPT-5.4 and DeepSeek-V4-Flash above 98\%. Yet, human evaluation shows that fluent explanations often fail to preserve culturally conventionalized meanings, particularly for proverbs that rest on historical allusions, and are correspondingly less useful for learners. Few-shot demonstrations benefit some weaker models in open-ended explanation but do not consistently help stronger ones. These findings suggest that selection accuracy alone does not capture proverb understanding, and that Mandarin proverbs remain a demanding task for evaluating how LLMs handle figurative and culturally embedded language.},
  url       = {https://aclanthology.org/2026.latell-1.17}
}
```
