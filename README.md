This repository contains codes accompanying our paper:

### Asymptotics of Protein Number Distribution in Stochastic Gene Expression Models under Burst Approximation

##### Yuntao Lu and Yunxin Zhang  

##### School of Mathematical Sciences, Fudan University, Shanghai 200433, China  

##### Email: `yuntaolu@berkeley.edu` and `xyz@fudan.edu.cn`  

##### Main text available through ``arXiv: 2511.14913`` (``Submitted to Physical Review Research``)

---

##### Contents

- 11 Jupyter Notebooks
- 6 PDF files
-  80 NumPy files

All numerical results and figures reported in our study, except for Figure 1, are fully accessible and reproducible using the resources available in this repository.

---

##### Directory Tree Structure

```
Stochastic_Translation/
├── README.md
├── Fig1/
│   └── Fig1.pdf
├── Fig2/
│   ├── binomial_moments_solver/
│   ├── fsp_results/
│   ├── ssa_outputs/
│   ├── binomial_moments_solver.ipynb
│   ├── Fig2.ipynb
│   ├── FSP.ipynb
│   ├── SSA.ipynb
│   └── Fig2.pdf
├── Fig3/
│   ├── fig3_data/
│   ├── Fig3.ipynb
│   ├── truncate.ipynb
│   └── Fig3.pdf
├── Fig4/
│   ├── Bound_Appr.ipynb
│   └── Fig4.pdf
├── FigS1/
│   ├── PMF_Bounds/
│   ├── FigS1.ipynb
│   ├── PMF_Bound.ipynb
│   └── FigS1.pdf
└── FigS2/
    ├── Binomial_Bound/
    ├── Binomial_Bound.ipynb
    ├── FigS2.ipynb
    └── FigS2.pdf

```

---

##### Environment

```
pip install numpy scipy matplotlib gillespy2
```

