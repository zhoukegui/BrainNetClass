# BrainNetClass
The aim of this toolbox is to make it easier for neuroscientists and clinicians to conduct state-of-the-art brain network 
construction and rigorous machine learning-based classifications.
  
## Requirements
  
  * SLEP
  * Libsvm
 
 These two toolboxes are included in the repository but may need to be complied in your own computer.
 
 ## Example Dataset
  
The repository provides a usage example on the eyes closed/eyes open dataset. 
The goal is to use resting-state fMRI time series from 116 brain regions to construct brain functional networks 
and predict whether the subject is in eyes closed state or eyes open state. 
There is a full version (with longer running time but better classification result) and 
a simplified version of the data (with shorter running time, for fast running).


We are glad to announce that our new brain network construction & classification toolbox, BrainNetClass v1.0, has been released on Github (https://github.com/zzstefan/BrainNetClass). It is a Matlab-based, open-coded, user-friendly brain functional connectivity network-based disease classification toolbox that automatically conducts functional network construction, network feature extraction and selection, parameter optimization, classification, and result demonstration. It was designed to help neuroscientists, doctors, or researchers in other fields easily and correctly work on brain functional connectome with state-of-the-art algorithms and conduct rigorous individualized disease classification or other machine learning tasks. It is hoped that this toolbox could be of help in standardization the methodology and boost reproducibility, generalizability, and interpretability of the results. 

Specifically, BrainNetClass v1.0 provides abundant means of brain functional network construction, including those recently developed for defining “high-order” functional networks and those utilizing sparse representation with biologically meaningful constraint for robust and consistent network construction. What’s more, it provides standard yet rigorous network-based classification with choices for feature extraction, feature reduction, cross-validation, and performance evaluation. Importantly, it does not stop at providing simple numbers like diagnosis accuracy. Instead, BrainNetClass v1.0 offers a comprehensive battery of result evaluation, including the receiver operating characteristic curve, suggestive parameters for future use, and the model robustness test, in addition to a full log of results for a hassle-free report. With a simple configuration on a GUI interface, all these results and reports are a quick click of the “Run” button away.  For details, please see the manual; exemplary data are provided for a quick walkthrough. The corresponding paper will be openly accessible soon.

BrainNetClass v1.0 is developed by the Image Display, Enhancement, and Analysis (IDEA) Laboratory, Department of Radiology and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill. We would like to thank Xiaobo Chen, Yu Zhang, Lishan Qiao, Renping Yu for their contributions. It is supported by NIH grants EB022880 and AG041721. Please contact Zhen Zhou (zzstefan@email.unc.edu), Han Zhang (hanzhang@med.unc.edu), and Dinggang Shen (dgshen@med.unc.edu) for any correspondence.
