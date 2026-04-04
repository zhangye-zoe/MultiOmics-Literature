## 📚 Multi-Omics Literature Collection


This repository curates representative papers in **multi-omics research**, along with **personal Writing notes**. The collection is updated periodically to track recent advances in **computational biology**. 📬 **Contact:** If you have questions and suggestions, feel free to reach out **Ye Zhang** at **zhangye_zoe@163.com**

---

## 📑 Table of Contents

- [📚 00. Review Article](#00-review-article)

- [🧬 01. Multi-omics Integration](#01-multi-omics-integration)
  <!-- - [Single-Cell Model](#single-cell-model)
  - [Spatial Model](#spatial-model) -->

- [🧠 02. Regulatory Inference](#02-regulatory-inference)

- [🧭 03. Trajectory Inference](#03-trajectory-inference)

- [🧪 04. Perturbution Analysis](#04-perturbution-analysis)

- [🧩 05. Representation Learning](#05-representation-learning)

- [🧬 06. Multi-omics Generation](#06-multi-omics-generation)

- [🔬 07. Omics and Pathology](#07-omics-and-pathology)

- [🧊 08. Spatial Omics Alignment](#08-spatial-omics-alignment)

<!-- - [📊 09. Models, Tasks and Datasets Summary](#09-models-tasks-and-datasets-summary) -->

---

### 00. Review Article


- **[Longitudinal omics data analysis: approaches and applications](https://www.sciencedirect.com/science/article/pii/S2001037026000012)** `Computational and Structural Biotechnology Journal, 2026`  
  [![Paper](https://img.shields.io/badge/Paper-Survey-hotpink)](https://www.sciencedirect.com/science/article/pii/S2001037026000012) [![Status](https://img.shields.io/badge/Status-Note-orange)](#)  
  > The paper reviews statistical and computational methods for analyzing longitudinal omics data. It summarizes modeling approaches, functional data analysis, classification, survival analysis, and emerging methods for multi-omics integration and network-based modeling.


- **[A technical review of multi-omics data integration methods: from classical statistical to deep generative approaches](https://academic.oup.com/bib/article/26/4/bbaf355/8220754?utm_source=chatgpt.com&login=false)**  `Briefings in Bioinformatics, 2025`  
  [![Paper](https://img.shields.io/badge/Paper-Survey-hotpink)](https://academic.oup.com/bib/article/26/4/bbaf355/8220754?utm_source=chatgpt.com&login=false) [![Status](https://img.shields.io/badge/Status-Note-orange)](https://zhangye-zoe.github.io/Status/scMRDR)  
  > The paper summarizes multi-omics integration methods ranging from classical statistical models to modern deep learning approaches. The statistical approaches include correlation- and covariance-based methods, matrix factorization, probabilistic models, and kernel methods. The deep learning approaches include neural networks, graph neural networks, variational autoencoders, and methods incorporating maximum mean discrepancy regularization.




- **[A comprehensive review of spatial transcriptomics data alignment and integration](https://academic.oup.com/nar/article/53/12/gkaf536/8174767?login=false)**  `Nucleic Acids Research, 2025`   
  [![Paper](https://img.shields.io/badge/Paper-Survey-hotpink)](https://academic.oup.com/nar/article/53/12/gkaf536/8174767?login=false) [![Status](https://img.shields.io/badge/Status-Note-orange)](https://zhangye-zoe.github.io/Status/scMRDR)  
  > The study reviews methodologies for spatial transcriptomics data alignment and integration, discusses key challenges, and proposes a general analysis pipeline. Existing approaches are categorized into statistical mapping, image processing and registration, and graph-based methods according to this framework.

- **[Omics data integration in computational biology viewed through the prism of machine learning paradigms](https://www.frontiersin.org/journals/bioinformatics/articles/10.3389/fbinf.2023.1191961/full)**  `Frontiers in Bioinformatics, 2023`  
  [![Paper](https://img.shields.io/badge/Paper-Survey-hotpink)](https://www.frontiersin.org/journals/bioinformatics/articles/10.3389/fbinf.2023.1191961/full) [![Status](https://img.shields.io/badge/Status-Note-orange)](https://zhangye-zoe.github.io/Status/scMRDR)  
  > The paper systematically reviews the paradigms, methods, and datasets developed for multi-omics data integration. The survey categorizes existing approaches into vertical integration, horizontal integration, and diagonal / mosaic integration.

  > <strong><span style="color:rgb(110, 18, 150);"> ⭐ Recommended as a starting review for researchers new to this field.</span></strong>


- **[Computational principles and challenges in single-cell data integration](https://www.nature.com/articles/s41587-021-00895-7)**  `Nature Biotechnology, 2021`  
  [![Paper](https://img.shields.io/badge/Paper-Survey-hotpink)](https://www.nature.com/articles/s41587-021-00895-7) [![Status](https://img.shields.io/badge/Status-Note-orange)](https://zhangye-zoe.github.io/Status/scMRDR)  
  > This is an authoritative review paper that introduces and defines several fundamental concepts in single-cell multi-omics integration.


- **[A Review of Integrative Imputation for Multi-Omics Datasets](https://www.frontiersin.org/journals/genetics/articles/10.3389/fgene.2020.570255/full)**  `Frontiers in Genetics, 2020`  
  [![Paper](https://img.shields.io/badge/Paper-Survey-hotpink)](https://www.frontiersin.org/journals/genetics/articles/10.3389/fgene.2020.570255/full) [![Status](https://img.shields.io/badge/Status-Note-orange)](https://zhangye-zoe.github.io/Status/scMRDR)  
  > The paper provides a summary of imputation methods used in multi-omics datasets, covering approaches such as single-omics imputation, genotype imputation, gene expression data imputation, and epigenomic data imputation.


---

### 01. Multi-omics Integration
**Single-Cell Model**


- **[Bridging Unpaired Single-Cell Multimodal Data for Integrative Analyses with SuperMap](https://www.nature.com/articles/s41467-025-60333-z)** `Proceedings of the National Academy of Sciences (PNAS), 2026`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/sjl-sjtu/scMRDR) [![Status](https://img.shields.io/badge/Status-Note-orange)](https://zhangye-zoe.github.io/Status/scMRDR)  
  > The paper proposes a statistical framework for multi-omics alignment. Specifically, the ATAC modality is used to infer the unobserved RNA modality, while enforcing a distributional constraint to ensure that the inferred RNA follows a similar distribution as the observed RNA.



- **[scMRDR: A Scalable and Flexible Framework for Unpaired Single-Cell Multi-Omics Data Integration](https://arxiv.org/abs/2510.24987)**  `Neural Information Processing Systems (NeurIPS), 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/sjl-sjtu/scMRDR) [![Status](https://img.shields.io/badge/Status-Note-orange)](...) [![Spotlight](https://img.shields.io/badge/NeurIPS-Spotlight-purple)](https://openreview.net/forum?id=tI04KmK27S&referrer=%5Bthe%20profile%20of%20Peng%20Ye%5D(%2Fprofile%3Fid%3D~Peng_Ye4))
  > The paper proposes a β-VAE–based disentanglement framework that decomposes cellular representations into modality-shared and modality-specific latent components, and evaluates the proposed method on biological conservation, batch correction, and modality integration tasks.

- **[scMODAL: a general deep learning framework for comprehensive single-cell multi-omics data alignment with feature link](https://www.nature.com/articles/s41467-025-60333-z)** `Nature Communications, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/sjl-sjtu/scMRDR) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents

- **[Benchmarking algorithms for single-cell multi-omics prediction and integration](https://www.nature.com/articles/s41592-024-02429-w)** `Nature Methods, 2024`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/QuKunLab/MultiomeBenchmarking) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper proposes a

- **[Dictionary learning for integrative, multimodal and scalable single-cell analysis](https://www.nature.com/articles/s41592-024-02429-w)** `Nature Biotechnology, 2023`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](http://www.satijalab.org/seurat) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper proposes a 

- **[BABEL enables cross-modality translation between multiomic profiles at single-cell resolution](https://www.pnas.org/doi/abs/10.1073/pnas.2023070118)** `Proceedings of the National Academy of Sciences, 2021`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/wukevin/babel) [![Status](https://img.shields.io/badge/Status-Note-orange)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper proposes a 




**Spatial Model**

- **[Achieving spatial multi-omics integration from unaligned serial sections with DIME](https://www.biorxiv.org/content/10.64898/2026.02.25.707961v1)** `ArXiv, 2026`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/sjl-sjtu/scMRDR) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents


- **[Riemannian Metric Learning for Alignment of Spatial Multiomics](https://www.biorxiv.org/content/10.64898/2025.12.09.693237v1.abstract)** `ArXiv, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/raphael-group/MGW) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents 



- **[Spatial integration of multi-omics data from serial sections using the novel Multi-Omics Imaging Integration Toolset](https://academic.oup.com/gigascience/article/doi/10.1093/gigascience/giaf035/8131474)** `GigaScience, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/sjl-sjtu/scMRDR) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
    > The paper presents GreedyFHist aligning serial image  including H&E stained WSI image and MSI image.


---

### 02. Regulatory Inference


- **[MultiGATE: integrative analysis and regulatory inference in spatial multi-omics data via graph representation learning](https://www.nature.com/articles/s41467-025-63418-x)** `Nature Communications, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/sjl-sjtu/scMRDR) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents 



---


### 03. Trajectory Inference

- **[Inferring differential dynamics from multilineage, multi-omic, and multi-sample singlecell data with MultiVeloVAE](https://www.nature.com/articles/s41467-025-66287-6)** `Nature Communications, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/welch-lab/MultiVeloVAE) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR) [![Docs](https://img.shields.io/badge/Docs-MultiVeloVAE-brown)](https://multivelovae.readthedocs.io/en/latest/)
  > The paper presents 
  

- **[STORIES: learning cell fate landscapes from spatial transcriptomics using optimal transport](https://www.nature.com/articles/s41592-025-02855-4)** `Nature Methods, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/cantinilab/stories) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper propose STORIES based on optimal transport to infer cell trajectories from spatial transcriptomics data.
  
  > <strong><span style="color:rgb(110, 18, 150);"> ⭐ Worth Writing. </span></strong>
  


- **[TIVelo: RNA velocity estimation leveraging cluster-level trajectory inference](https://www.nature.com/articles/s41467-025-61628-x)** `Nature Communications, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/cuhklinlab/TIVelo) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR) [![Docs](https://img.shields.io/badge/Docs-TIVelo-brown)](https://tivelo.readthedocs.io/en/latest/)
  > The paper presents


- **[Multivariate stochastic modeling for transcriptional dynamics with cell-specific latent time using SDEvelo](https://www.nature.com/articles/s41467-024-55146-5)** `Nature Communications, 2024`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/welch-lab/VeloVAE) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents

- **[DeepVelo: deep learning extends RNA velocity to multi-lineage systems with cell-specific kinetics](https://link.springer.com/article/10.1186/s13059-023-03148-9)** `Genome Biology, 2024`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/bowang-lab/DeepVelo) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents


- **[A relay velocity model infers cell-dependent RNA velocity](https://www.nature.com/articles/s41587-023-01728-5)** `Nature Biotechnology, 2023`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/GuangyuWangLab2021/cellDancer) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents


- **[Deep generative modeling of transcriptional dynamics for RNA velocity analysis in single cells](https://www.nature.com/articles/s41592-023-01994-w)** `Nature Methods, 2023`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/YosefLab/velovi) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents




- **[GraphVelo allows for accurate inference of multimodal velocities and molecular mechanisms for single cells](https://www.nature.com/articles/s41467-025-62784-w)** `Nature Communications, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/xing-lab-pitt/GraphVelo) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR) [![Docs](https://img.shields.io/badge/Docs-GraphVelo-brown)](https://graphvelo.readthedocs.io/en/latest/)
  > The paper presents



- **[Multi-omic single-cell velocity models epigenome–transcriptome interactions and improves cell fate prediction](https://www.nature.com/articles/s41587-022-01476-y)** `Nature Biotechnology, 2022`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/welch-lab/MultiVelo) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR) [![Docs](https://img.shields.io/badge/Docs-MultiVelo-brown)](https://multivelo.readthedocs.io/en/latest/)
  > The paper presents 

- **[UniTVelo: temporally unified RNA velocity reinforces single-cell trajectory inference](https://www.nature.com/articles/s41467-022-34188-7)** `Nature Communications, 2022`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/StatBiomed/UniTVelo) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents 


- **[Generalizing RNA velocity to transient cell states through dynamical modeling](https://www.nature.com/articles/s41587-020-0591-3)** `Nature Biotechnology, 2022`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/theislab/scvelo) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR) [![Docs](https://img.shields.io/badge/Docs-ScVelo-brown)](https://scvelo.readthedocs.io/en/stable/)
  > The paper presents 


- **[Pyro-Velocity: Probabilistic RNA Velocity inference  from single-cell data](https://www.biorxiv.org/content/10.1101/2022.09.12.507691v1)** `ArXiv, 2022`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/pinellolab/pyrovelocity) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents 



---


### 04. Perturbution Analysis

- **[An expanded registry of candidate cis-regulatory elements](https://www.nature.com/articles/s41586-025-09909-9)** `Nature, 2026`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/weng-lab/ENCODE-cCREs/tree/master/Version-4) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The study expands the ENCODE registry to 2.37 million human and 967,000 mouse candidate cis-regulatory elements (cCREs), providing a comprehensive resource for studying gene regulation.

- **[Squidiff: predicting cellular development and responses to perturbations using a diffusion model](https://www.nature.com/articles/s41592-025-02877-y)** `Nature Methods, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/siyuh/Squidiff) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper proposes Squidiff, a diffusion-based generative framework designed to predict transcriptomic responses to environmental perturbations. The proposed method is evaluated on multiple biological tasks, including cell differentiation, gene perturbation, and drug response prediction.


- **[Pertpy: an end-to-end framework for perturbation analysis](https://www.nature.com/articles/s41592-025-02909-7)** `Nature Methods, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/scverse/pertpy) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper introduces



- **[Predicting cell morphological responses to perturbations using generative modeling](https://www.nature.com/articles/s41467-024-55707-8)** `Nature Communications, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/theislab/IMPA) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper introduces IMPA, a generative style-transfer model designed to predict cell morphology under genetic perturbations and chemical treatments. Experiments demonstrate that IMPA effectively captures both morphological and population-level variations in breast cancer and osteosarcoma cells.


- **[PerturBench: Benchmarking Machine Learning Models for Cellular Perturbation Analysis](https://arxiv.org/abs/2408.10609)** `ArXiv, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/altoslabs/perturbench/) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents


- **[Mapping and reprogramming human tissue  microenvironments with MintFlow](https://arxiv.org/abs/2408.10609)** `ArXiv, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/Lotfollahi-lab/mintflow-reproducibility) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents


- **[Predicting cellular responses to perturbation across diverse contexts with State](https://arxiv.org/abs/2408.10609)** `ArXiv, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/ArcInstitute/State) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents


- **[Predicting transcriptional outcomes of novel multigene perturbations with GEARS](https://www.nature.com/articles/s41587-023-01905-6)** `Nature Biotechnology, 2024`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/snap-stanford/GEARS) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper introduces

- **[Unified multimodal learning enables generalized cellular response prediction to diverse perturbations](https://www.biorxiv.org/content/10.1101/2025.11.13.688367v2.full.pdf)** `Nature Biotechnology, 2024`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/Chen-Li-17/X-Pert) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper introduces


---


### 05. Representation Learning


- **[Causal disentanglement for single-cell representations and controllable counterfactual generation](https://www.nature.com/articles/s41467-025-62008-1)** `Nature Communications, 2025`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/bm2-lab/CausCell) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR) [![Docs](https://img.shields.io/badge/Docs-SIMBA-brown)](https://simba-bio.readthedocs.io//)
  > The paper proposes CausCell, a diffusion-based framework designed to disentangle cellular representations from spatiotemporal omics data. The method is evaluated in both disentanglement and reconstruction scenarios, demonstrating superior performance compared with existing approaches.

- **[SIMBA: single-cell embedding along with features](https://www.nature.com/articles/s41592-023-01899-8)** `Nature Methods, 2024`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/pinellolab/simba) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR) [![Docs](https://img.shields.io/badge/Docs-SIMBA-brown)](https://simba-bio.readthedocs.io//)
  > The paper presents 

- **[Joint variational autoencoders for multimodal imputation and embedding](https://www.nature.com/articles/s42256-023-00663-z)** `Nature Biotechnology, 2022`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/daifengwanglab/JAMIE) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper presents 


---

### 06. Multi-omics Generation

- **[Predicting transcriptional outcomes of novel multigene perturbations with GEARS](https://www.nature.com/articles/s41587-023-01905-6)** `Nature Biotechnology, 2024`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/snap-stanford/GEARS) [![Status](https://img.shields.io/badge/Status-Writing-blue)](https://zhangye-zoe.github.io/Status/scMRDR)
  > The paper introduces


---


### 07. Omics and Pathology

- **[LazySlide: accessible and interoperable whole-slide image analysis](https://www.nature.com/articles/s41592-026-03044-7)** `Nature Methods, 2026`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/RendeiroLab/LazySlide) [![Status](https://img.shields.io/badge/Status-Note-orange)](https://zhangye-zoe.github.io/Status/scMRDR) [![Docs](https://img.shields.io/badge/Docs-LazySlide-brown)](https://lazyslide.readthedocs.io/en/stable/)
  > The paper presents a pathology analysis tool that supports patch splitting, feature extraction, cell segmentation, and other workflows in pathology image analysis. In addition, the tool supports integration with omics data.


### 08. Spatial Omics Alignment

- **[LazySlide: accessible and interoperable whole-slide image analysis](https://www.nature.com/articles/s41592-026-03044-7)** `Nature Methods, 2026`  
  [![Code](https://img.shields.io/badge/Code-GitHub-brightgreen)](https://github.com/RendeiroLab/LazySlide) [![Status](https://img.shields.io/badge/Status-Note-orange)](https://zhangye-zoe.github.io/Status/scMRDR) [![Docs](https://img.shields.io/badge/Docs-LazySlide-brown)](https://lazyslide.readthedocs.io/en/stable/)
  > The paper presents a pathology analysis tool that supports patch splitting, feature extraction, cell segmentation, and other workflows in pathology image analysis. In addition, the tool supports integration with omics data.
