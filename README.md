# Awesome Passage Retrieval [![Awesome](https://awesome.re/badge.svg)](https://github.com/zmzhang2000/awesome-passage-retrieval)

A curated list of awesome ***Passage Retrieval*** papers and resources. 

Passage retrieval is to learn text retrieval models for downstream tasks, *e.g.*, Question Answering.

## Contributing

Please feel free to send a pull request for valuable papers or resources.

## Contents

- [Papers](#papers)

    - [2022](#2022)
    - [2021](#2021)
    - [2020](#2020)
    - [2019](#2019)
    - [2017](#2017)

- [Resources](#resources)

## Papers

### 2022

- **Hyperlink-induced Pre-training for Passage Retrieval in Open-domain Question Answering** \
    *Jiawei Zhou, Xiaoguang Li, Lifeng Shang, Lan Luo, Ke Zhan, Enrui Hu, Xinyu Zhang, Hao Jiang, Zhao Cao, Fan Yu, Xin Jiang, Qun Liu, Lei Chen* \
    ACL, 2022. [[Paper](http://arxiv.org/abs/2203.06942)] [[Code](https://github.com/jzhoubu/HLP)]

- **Unsupervised Corpus Aware Language Model Pre-training for Dense Passage Retrieval** \
    *Luyu Gao and Jamie Callan* \
    ACL, 2022. [[Paper](http://arxiv.org/abs/2108.05540)] [[Code](https://github.com/luyug/Condenser)]

- **Sentence-aware Contrastive Learning for Open-Domain Passage Retrieval** \
    *Bohong Wu, Zhuosheng Zhang, JinyuanWang, Hai Zhao* \
    ACL, 2022. [[Paper](http://arxiv.org/abs/2110.07524)] [[Code](https://github.com/chengzhipanpan/DCSR)]

### 2021

- **Neural Retrieval for Question Answering with Cross-Attention Supervised Data Augmentation** \ 
    *Yinfei Yang, Ning Jin, Kuo Lin, Mandy Guo, Daniel Cer* \
    ACL-IJCNLP, 2021. [[Paper](https://aclanthology.org/2021.acl-short.35)]

- **End-to-End Training of Neural Retrievers for Open-Domain Question Answering** \
    *Devendra Singh Sachan, Mostofa Patwary, Mohammad Shoeybi, Neel Kant, Wei Ping, William L Hamilton, Bryan Catanzaro* \
    ACL-IJCNLP, 2021. [[Paper](https://aclanthology.org/2021.acl-long.519)] [[Code](https://github.com/NVIDIA/Megatron-LM)]

- **Improving Document Representations by Generating Pseudo Query Embeddings for Dense Retrieval** \ 
    *Hongyin Tang, Xingwu Sun, Beihong Jin, JingangWang, Fuzheng Zhang, Wei Wu* \
    ACL-IJCNLP, 2021. [[Paper](https://aclanthology.org/2021.acl-long.392)]

- **xMoCo: Cross Momentum Contrastive Learning for Open-Domain Question Answering** \
    *Nan Yang, Furu Wei, Binxing Jiao, Daxin Jiang, Linjun Yang* \
    ACL-IJCNLP, 2021. [[Paper](https://aclanthology.org/2021.acl-long.477)]

- **PAIR: Leveraging Passage-Centric Similarity Relation for Improving Dense Passage Retrieval** \
    *Ruiyang Ren, Shangwen Lv, Yingqi Qu, Jing Liu, Wayne Xin Zhao, Qiaoqiao She, Hua Wu, Haifeng Wang, and Ji-Rong Wen* \
    ACL-IJCNLP, 2021. [[Paper](https://aclanthology.org/2021.findings-acl.191)] [[Code](https://github.com/PaddlePaddle/RocketQA/tree/main/research/PAIR_ACL2021)]

- **Condenser: a Pre-training Architecture for Dense Retrieval** \
    *Luyu Gao and Jamie Callan* \
    EMNLP, 2021. [[Paper](https://aclanthology.org/2021.emnlp-main.75)] [[Code](https://github.com/luyug/Condenser)]

- **RocketQAv2: A Joint Training Method for Dense Passage Retrieval and Passage Re-ranking** \
    *Ruiyang Ren, Yingqi Qu, Jing Liu, Wayne Xin Zhao, Qiaoqiao She, Hua Wu, Haifeng Wang, and Ji-Rong Wen* \
    EMNLP, 2021. [[Paper](10.18653/v1/2021.emnlp-main.224)] [[Code](https://github.com/PaddlePaddle/RocketQA/tree/main/research/RocketQAv2_EMNLP2021)]

- **RocketQA: An Optimized Training Approach to Dense Passage Retrieval for Open-Domain Question Answering** \
    *Yingqi Qu, Yuchen Ding, Jing Liu, Kai Liu, Ruiyang Ren, Wayne Xin Zhao, Daxiang Dong, Hua Wu and Haifeng Wang* \
    NAACL, 2021. [[Paper](http://arxiv.org/abs/2010.08191)] [[Code](https://github.com/PaddlePaddle/RocketQA/tree/main/research/RocketQA_NAACL2021)]

- **Scaling Deep Contrastive Learning Batch Size under Memory Limited Setup** \
    *Luyu Gao, Yunyi Zhang, Jiawei Han, Jamie Callan* \
    RepL4NLP, 2021. [[Paper](https://aclanthology.org/2021.repl4nlp-1.31/)] [[Code](https://github.com/luyug/GradCache)]

- **Distilling Knowledge from Reader to Retriever for Question Answering** \
    *Gautier Izacard, Edouard Grave* \
    ICLR, 2021. [[Paper](https://openreview.net/forum?id=NTEz-6wysdb)] [[Code](github.com/facebookresearch/FiD)]

- **Approximate Nearest Neighbor Negative Contrastive Learning for Dense Text Retrieval** \
    *Lee Xiong, Chenyan Xiong, Ye Li, Kwok-Fung Tang, Jialin Liu, Paul Bennett, Junaid Ahmed, Arnold Overwijk* \
    ICLR, 2021. [[Paper](https://openreview.net/forum?id=zeFrfgyZln)] [[Code](http://aka.ms/ance)]

- **A Replication Study of Dense Passage Retriever** \
    *Xueguang Ma, Kai Sun, Ronak Pradeep, and Jimmy Lin* \
    arXiv, 2021. [[Paper](http://arxiv.org/abs/2104.05740)] [[Code](http://pyserini.io/)]

### 2020

- **Neural Passage Retrieval with Improved Negative Contrast** \
    *Jing Lu, Gustavo Hernandez Abrego, Ji Ma, Jianmo Ni, Yinfei Yang* \
    arXiv, 2020. [[Paper](http://arxiv.org/abs/2010.12523)]

- **Dense Passage Retrieval for Open-Domain Question Answering** \
    *Vladimir Karpukhin, Barlas Oguz, Sewon Miny, Patrick Lewis, Ledell Wu, Sergey Edunov, Danqi Chen, Wen-tau Yih* \
    EMNLP, 2020. [[Paper](http://arxiv.org/abs/2004.04906)] [[Code](https://github.com/facebookresearch/DPR)]

### 2019

- **Latent Retrieval forWeakly Supervised Open Domain Question Answering** \
    *Kenton Lee, Ming-Wei Chang, Kristina Toutanova* \
    ACL, 2019. [[Paper](https://aclanthology.org/P19-1612)]

### 2017

- **ReadingWikipedia to Answer Open-Domain Questions** \
    *Danqi Chen, Adam Fisch, Jason Weston, Antoine Bordes* \
    ACL, 2017. [[Paper](https://aclanthology.org/P17-1171/)] [[Code](https://github.com/facebookresearch/DrQA)]

## Resources

- **Gradient Cached Dense Passage Retrieval** \
    [[Github](https://github.com/facebookresearch/DrQA)]

