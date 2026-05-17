---
title:          "DecoyDB: A Dataset for Graph Contrastive Learning in Protein-Ligand Binding Affinity Prediction"
date:           2025-11-10 00:01:00 +0800
selected:       true
pub:            "The 39th Annual Conference on Neural Information Processing Systems (NeurIPS 2025)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
# pub_date:       "2025"

abstract: >-
  We propose DecoyDB, a large-scale, structure-aware dataset specifically designed for self-supervised graph contrastive learning (GCL) on protein–ligand complexes. DecoyDB consists of high-resolution ground truth complexes and diverse decoy structures with computationally generated binding poses that range from realistic to suboptimal. Each decoy is annotated with a Root Mean Square Deviation (RMSD) from the native pose. We further design a customized GCL framework to pretrain graph neural networks based on DecoyDB and fine-tune the models with labels from PDBbind. Extensive experiments confirm that models pretrained with DecoyDB achieve superior accuracy, sample efficiency, and generalizability.
cover:          /assets/images/covers/NeurIPS25_DecoyDB.jpg
authors:
  - Yupu Zhang
  - Zelin Xu
  - <strong>Tingsong Xiao</strong>
  - Gustavo Seabra
  - Yanjun Li
  - Chenglong Li
  - Zhe Jiang
links:
  Paper: https://openreview.net/forum?id=lzLo5bRgQC
  Dataset: https://huggingface.co/datasets/jiangteam/DecoyDB
---
