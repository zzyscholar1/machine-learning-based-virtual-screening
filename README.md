# Machine Learning-Based Virtual Screening and Identification of the Fourth-Generation EGFR Inhibitors

## Background

The Epidermal Growth Factor Receptor (EGFR) plays a critical role in the treatment of advanced non-small cell lung cancer (NSCLC). However, the emergence of the tertiary **C797S mutation**—particularly in combination with L858R/T790M or Del19/T790M—has rendered existing EGFR inhibitors ineffective.

This creates an urgent need for the development of **fourth-generation EGFR tyrosine kinase inhibitors (EGFR-TKIs)**.

---

## Objective

This project aims to identify novel fourth-generation EGFR inhibitors using machine learning-based virtual screening techniques.
<img width="624" height="261" alt="Screenshot 2026-03-02 at 9 13 46 PM" src="https://github.com/user-attachments/assets/64fc8041-7bfd-489b-9ae4-1a0cc007ab58" />


---

## Methodology

The dataset used in this study was:

- High-dimensional  
- Sparse  
- Containing both structured and unstructured molecular descriptors  

To address these challenges, we developed a **fusion feature selection framework** that integrates:

- Full Quadratic Effect (FQE) Model  
- Lasso Regression Model  

This hybrid approach allowed us to:

- Identify critical molecular descriptors  
- Reduce dimensionality  
- Improve model interpretability

<img width="567" height="244" alt="Screenshot 2026-03-02 at 9 15 36 PM" src="https://github.com/user-attachments/assets/e70de366-9d51-451e-aff4-7a1156905cd8" />


---

## Drug Design & Experimental Validation

Based on structural descriptors identified by the FQE model, we designed and synthesized a series of small-molecule inhibitors.

These compounds demonstrated strong inhibitory activity against:

- L858R/T790M/C797S mutation  
- Del19/T790M/C797S mutation  

---

## Virtual Screening Results

Using our trained model, we conducted virtual screening and successfully identified **four promising hit compounds**.

We further evaluated:

- ADME properties  
- Drug-likeness characteristics  

Future work includes experimental biological activity validation to advance the discovery of next-generation EGFR-TKIs.

---

## Impact

This study demonstrates how machine learning can accelerate drug discovery by:

- Enhancing molecular feature selection  
- Improving predictive modeling accuracy  
- Reducing experimental search space  
- Identifying promising drug candidates efficiently  

---

## Publication

Published in: *ACS Omega*  
Field: Machine Learning in Computational Chemistry
