# Training and validation datasets

This repository provides the training and validation datasets used for constructing the machine-learned potential in the following paper:

```bibtex
@article{PhysRevMaterials.9.053805,
  title = {Efficient moment tensor machine-learning interatomic potential for accurate description of defects in Ni-Al Alloys},
  author = {Wang, Jiantao and Liu, Peitao and Zhu, Heyu and Liu, Mingfeng and Ma, Hui and Chen, Yun and Sun, Yan and Chen, Xing-Qiu},
  journal = {Phys. Rev. Mater.},
  volume = {9},
  issue = {5},
  pages = {053805},
  numpages = {23},
  year = {2025},
  month = {May},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevMaterials.9.053805},
  url = {https://link.aps.org/doi/10.1103/PhysRevMaterials.9.053805}
}
```

train.1.xyz + train.2.xyz: Training dataset (Note that due to the file size limitations of github, the training dataset is split into two files and one can obtain the the whole training dataset by "cat train.1.xyz train.2.xyz > train.xyz")

valid.xyz: Validation dataset

potential.mtp: MTP potential file ( type 0 is Al, type 1 is Ni)
