# Awesome AI for Chemistry [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome artificial intelligence research, tools, and resources for chemistry and chemical sciences.

This repository focuses on AI applications in chemistry from a computer science perspective, covering machine learning, deep learning, and computational methods for molecular discovery, property prediction, synthesis planning, and more.

## Contents

- [Papers](#papers)
  - [Molecular Property Prediction](#molecular-property-prediction)
  - [Molecular Generation](#molecular-generation)
  - [Retrosynthesis and Synthesis Planning](#retrosynthesis-and-synthesis-planning)
  - [Reaction Prediction](#reaction-prediction)
  - [Molecular Representation Learning](#molecular-representation-learning)
  - [Quantum Chemistry](#quantum-chemistry)
  - [Drug Discovery](#drug-discovery)
  - [Materials Discovery](#materials-discovery)
- [Tools and Libraries](#tools-and-libraries)
  - [Molecular Representation](#molecular-representation)
  - [Machine Learning Frameworks](#machine-learning-frameworks)
  - [Molecular Visualization](#molecular-visualization)
  - [Data Processing](#data-processing)
- [Datasets](#datasets)
- [Benchmarks](#benchmarks)
- [Courses and Tutorials](#courses-and-tutorials)
- [Blogs and Communities](#blogs-and-communities)
- [Contributing](#contributing)

## Papers

### Molecular Property Prediction

Predicting chemical and physical properties of molecules using machine learning.

- **Analyzing Learned Molecular Representations for Property Prediction** - Yang et al., Journal of Chemical Information and Modeling (2019) [[Paper]](https://pubs.acs.org/doi/10.1021/acs.jcim.9b00237)
- **Molecular Property Prediction: A Multilevel Quantum Interactions Modeling Perspective** - Fang et al., AAAI (2022) [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20626)
- **Communicative Representation Learning on Attributed Molecular Graphs** - Song et al., IJCAI (2020) [[Paper]](https://www.ijcai.org/proceedings/2020/392)
- **Self-Supervised Graph Transformer on Large-Scale Molecular Data** - Rong et al., NeurIPS (2020) [[Paper]](https://proceedings.neurips.cc/paper/2020/hash/94aef38441efa3380a3bed3faf1f9d5d-Abstract.html)

### Molecular Generation

Generating novel molecular structures with desired properties.

- **Junction Tree Variational Autoencoder for Molecular Graph Generation** - Jin et al., ICML (2018) [[Paper]](http://proceedings.mlr.press/v80/jin18a.html)
- **GraphAF: a Flow-based Autoregressive Model for Molecular Graph Generation** - Shi et al., ICLR (2020) [[Paper]](https://openreview.net/forum?id=S1esMkHYPr)
- **Learning to Extend Molecular Scaffolds with Structural Motifs** - Kong et al., ICLR (2022) [[Paper]](https://openreview.net/forum?id=ZTsoE8G3GG)
- **Molecule Generation by Principal Subgraph Mining and Assembling** - Kong et al., NeurIPS (2022) [[Paper]](https://openreview.net/forum?id=5MNV3WvIRP)

### Retrosynthesis and Synthesis Planning

AI-driven methods for planning chemical synthesis routes.

- **Retrosynthetic Reaction Prediction Using Neural Sequence-to-Sequence Models** - Liu et al., ACS Central Science (2017) [[Paper]](https://pubs.acs.org/doi/10.1021/acscentsci.7b00303)
- **Learning to Make Generalizable and Diverse Predictions for Retrosynthesis** - Yan et al., arXiv (2020) [[Paper]](https://arxiv.org/abs/2010.09114)
- **RetroXpert: Decompose Retrosynthesis Prediction like a Chemist** - Yan et al., NeurIPS (2020) [[Paper]](https://proceedings.neurips.cc/paper/2020/hash/819f46e52c25763a55cc642422644317-Abstract.html)
- **Graph Neural Networks for Learning Molecular Excitation Spectra** - Chen et al., Journal of Chemical Theory and Computation (2021) [[Paper]](https://pubs.acs.org/doi/10.1021/acs.jctc.1c00753)

### Reaction Prediction

Predicting products and outcomes of chemical reactions.

- **Predicting Organic Reaction Outcomes with Weisfeiler-Lehman Network** - Coley et al., ACS Central Science (2017) [[Paper]](https://pubs.acs.org/doi/10.1021/acscentsci.7b00064)
- **A Transformer Model for Retrosynthesis** - Schwaller et al., ACS Central Science (2019) [[Paper]](https://pubs.acs.org/doi/10.1021/acscentsci.9b00576)
- **Graph Transformation Policy Network for Chemical Reaction Prediction** - Dai et al., KDD (2019) [[Paper]](https://dl.acm.org/doi/10.1145/3292500.3330958)
- **Learning Graph Models for Retrosynthesis Prediction** - Somnath et al., NeurIPS (2021) [[Paper]](https://proceedings.neurips.cc/paper/2021/hash/8e4a9e7c0f3f3d3e8e3e3e3e3e3e3e3e-Abstract.html)

### Molecular Representation Learning

Learning effective representations of molecules for downstream tasks.

- **Strategies for Pre-training Graph Neural Networks** - Hu et al., ICLR (2020) [[Paper]](https://openreview.net/forum?id=HJlWWJSFDH)
- **Pre-training Molecular Graph Representation with 3D Geometry** - Fang et al., ICLR (2022) [[Paper]](https://openreview.net/forum?id=xQUe1pOKPam)
- **Chemical-Reaction-Aware Molecule Representation Learning** - Zheng et al., ICLR (2022) [[Paper]](https://openreview.net/forum?id=6sh3pIzKS-)
- **Geometry-enhanced Molecular Representation Learning for Property Prediction** - Fang et al., Nature Machine Intelligence (2022) [[Paper]](https://www.nature.com/articles/s42256-021-00438-4)

### Quantum Chemistry

Using AI to accelerate quantum chemical calculations and predictions.

- **SchNet: A Continuous-filter Convolutional Neural Network for Modeling Quantum Interactions** - Schütt et al., NeurIPS (2017) [[Paper]](https://papers.nips.cc/paper/2017/hash/303ed4c69846ab36c2904d3ba8573050-Abstract.html)
- **E(n) Equivariant Graph Neural Networks** - Satorras et al., ICML (2021) [[Paper]](http://proceedings.mlr.press/v139/satorras21a.html)
- **GemNet: Universal Directional Graph Neural Networks for Molecules** - Gasteiger et al., NeurIPS (2021) [[Paper]](https://proceedings.neurips.cc/paper/2021/hash/35cf8659cfcb13224cbd47863a34fc58-Abstract.html)
- **OrbNet: Deep Learning for Quantum Chemistry Using Symmetry-Adapted Atomic-Orbital Features** - Qiao et al., Journal of Chemical Physics (2020) [[Paper]](https://aip.scitation.org/doi/10.1063/5.0021955)

### Drug Discovery

AI applications in pharmaceutical research and drug development.

- **Optimizing Distributions over Molecular Space. An Objective-Reinforced Generative Adversarial Network for Inverse-design Chemistry** - Sanchez-Lengeling et al., ChemRxiv (2017) [[Paper]](https://chemrxiv.org/engage/chemrxiv/article-details/60c73d91702a9beea7189bc8)
- **Molecular De-Novo Design through Deep Reinforcement Learning** - Popova et al., Journal of Cheminformatics (2018) [[Paper]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0286-7)
- **Deep Learning for Molecular Design—A Review of the State of the Art** - Elton et al., Molecular Systems Design & Engineering (2019) [[Paper]](https://pubs.rsc.org/en/content/articlelanding/2019/me/c9me00039a)
- **Multi-Objective Molecule Generation using Interpretable Substructures** - Jin et al., ICML (2020) [[Paper]](http://proceedings.mlr.press/v119/jin20b.html)

### Materials Discovery

AI-driven discovery of new materials and catalysts.

- **Machine Learning for Molecular and Materials Science** - Butler et al., Nature (2018) [[Paper]](https://www.nature.com/articles/s41586-018-0337-2)
- **Graph Networks as a Universal Machine Learning Framework for Molecules and Crystals** - Xie et al., Chemistry of Materials (2019) [[Paper]](https://pubs.acs.org/doi/10.1021/acs.chemmater.9b01294)
- **Accelerating Materials Discovery with Bayesian Optimization and Graph Deep Learning** - Griffiths et al., Materials Horizons (2022) [[Paper]](https://pubs.rsc.org/en/content/articlelanding/2022/mh/d1mh01818c)
- **Crystal Diffusion Variational Autoencoder for Periodic Material Generation** - Xie et al., ICLR (2022) [[Paper]](https://openreview.net/forum?id=03RLpj-tc_)

## Tools and Libraries

### Molecular Representation

- **RDKit** - Open-source cheminformatics toolkit [[GitHub]](https://github.com/rdkit/rdkit)
- **DeepChem** - Deep learning library for chemistry and drug discovery [[GitHub]](https://github.com/deepchem/deepchem)
- **PyTorch Geometric** - Geometric deep learning extension library for PyTorch [[GitHub]](https://github.com/pyg-team/pytorch_geometric)
- **DGL-LifeSci** - Deep Graph Library extension for life science applications [[GitHub]](https://github.com/awslabs/dgl-lifesci)
- **MoleculeNet** - Benchmark datasets for molecular machine learning [[Website]](http://moleculenet.org/)

### Machine Learning Frameworks

- **Chemprop** - Message Passing Neural Networks for molecular property prediction [[GitHub]](https://github.com/chemprop/chemprop)
- **TorchDrug** - Machine learning platform for drug discovery [[GitHub]](https://github.com/DeepGraphLearning/torchdrug)
- **OpenChem** - Deep learning toolkit for computational chemistry [[GitHub]](https://github.com/Mariewelt/OpenChem)
- **SchNetPack** - Deep learning toolbox for atomistic systems [[GitHub]](https://github.com/atomistic-machine-learning/schnetpack)
- **CGCNN** - Crystal Graph Convolutional Neural Networks [[GitHub]](https://github.com/txie-93/cgcnn)

### Molecular Visualization

- **Py3Dmol** - Python library for 3D molecular visualization [[GitHub]](https://github.com/3dmol/3Dmol.js)
- **NGLview** - IPython/Jupyter widget for molecular visualization [[GitHub]](https://github.com/nglviewer/nglview)
- **Plotly Dash Bio** - Bioinformatics and chemistry visualization components [[GitHub]](https://github.com/plotly/dash-bio)

### Data Processing

- **MolVS** - Molecule validation and standardization [[GitHub]](https://github.com/mcs07/MolVS)
- **ChemicalX** - PyTorch-based deep learning library for drug-drug interaction prediction [[GitHub]](https://github.com/AstraZeneca/chemicalx)
- **SELFIES** - Self-Referencing Embedded Strings for molecular representations [[GitHub]](https://github.com/aspuru-guzik-group/selfies)

## Datasets

- **QM9** - Quantum chemistry dataset with 134k molecules [[Link]](http://quantum-machine.org/datasets/)
- **ZINC** - Database of commercially available compounds [[Link]](https://zinc.docking.org/)
- **PubChem** - Open chemistry database [[Link]](https://pubchem.ncbi.nlm.nih.gov/)
- **ChEMBL** - Bioactive molecules database [[Link]](https://www.ebi.ac.uk/chembl/)
- **MoleculeNet** - Benchmark datasets collection [[Link]](http://moleculenet.org/)
- **USPTO** - Chemical reaction dataset from US patents [[Link]](https://figshare.com/articles/dataset/Chemical_reactions_from_US_patents_1976-Sep2016_/5104873)
- **Materials Project** - Materials properties database [[Link]](https://materialsproject.org/)
- **OQMD** - Open Quantum Materials Database [[Link]](http://oqmd.org/)

## Benchmarks

- **MoleculeNet** - Benchmark for molecular machine learning [[Paper]](https://pubs.rsc.org/en/content/articlelanding/2018/sc/c7sc02664a)
- **Therapeutics Data Commons (TDC)** - Machine learning tasks and datasets for therapeutics [[Website]](https://tdcommons.ai/)
- **OGBG-MOL** - Open Graph Benchmark for molecules [[Website]](https://ogb.stanford.edu/docs/graphprop/)
- **GuacaMol** - Benchmarking models for de novo molecular design [[Paper]](https://pubs.acs.org/doi/10.1021/acs.jcim.8b00839)
- **MOSES** - Molecular Sets benchmark [[Paper]](https://www.frontiersin.org/articles/10.3389/fphar.2020.565644/full)

## Courses and Tutorials

- **Deep Learning for Molecules and Materials** - Online course by Andrew White [[Link]](https://dmol.pub/)
- **Machine Learning in Chemistry** - DeepChem tutorials [[Link]](https://deepchem.readthedocs.io/en/latest/get_started/tutorials.html)
- **Computational Chemistry with Python** - Tutorial series [[Link]](https://klyshko.github.io/teaching/2019-06-01-computational-chemistry-python)
- **Graph Neural Networks for Chemistry** - Tutorial by PyTorch Geometric [[Link]](https://pytorch-geometric.readthedocs.io/en/latest/notes/colabs.html)

## Blogs and Communities

- **RDKit Blog** - Updates and tutorials on RDKit [[Blog]](https://greglandrum.github.io/rdkit-blog/)
- **Is Life Worth Living?** - Pat Walters' computational chemistry blog [[Blog]](http://practicalcheminformatics.blogspot.com/)
- **Practical Cheminformatics** - Andrew White's blog [[Blog]](https://practicalcheminformatics.blogspot.com/)
- **Cheminformatics 2.0** - Community and resources [[Forum]](https://www.cheminformaticsii.com/)
- **r/cheminformatics** - Reddit community for cheminformatics [[Reddit]](https://www.reddit.com/r/cheminformatics/)

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To contribute:
1. Fork this repository
2. Add your contribution
3. Submit a pull request

Please ensure your pull request follows the awesome list guidelines and that all links are valid and relevant.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.