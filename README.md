BC-CRC
# Bi-clustering based identification of colon cancer prognosis marker gene modules in complementary to CMS classification

Abstract
Transcriptomics data based Consensus Molecular Subtype (CMS) classification has been accepted as a standard rule for colorectal cancer (CRC) stratification. In this study, we developed a novel computational framework aiming to identify CMS stratification, prognosis, and drug resistance associated mechanisms, by conducting a bi-clustering based low rank gene expression modules in multiple large CRC transcriptomics data sets, and annotating the identified bi-clusters (BC) with their statistical associations to biological function, CMS classification and other clinicopathological information. Our analysis suggests that the bi-clustering based formulation cannot only identify alternative and disease subtype specific prognosis or drug resistance predictive markers but also generating new biological understanding to CRC stratification. Our key results include: (1) a comprehensive annotation of the BC landscape of CRC; (2) the BCs associated with CMS subclasses demonstrate the CMS IV is highly like a mixture of CMS I-III with high stromal infiltration while CMS I-III samples also contain certain cell populations show the characteristics of other classes; (3) BC based CMS dependent/independent prognosis markers suggests the disease progression free survival of CRC are largely determined by micro-environmental alterations while the overall survival is more associated with the level of stromal infiltration and CMS subtype markers; and (4) BC based predictive markers reveal alterative resistance mechanisms of Oxaliplatin, 5-Fluorouracil, and the FOLFOX therapy.

<br/>
<br/>
<br/>
<br/>



                                    The Analysis Pipeline of This Study
![image](https://github.com/changwn/BC-CRC/blob/master/CRC_figure/fig1.jpg)

# SUPPLEMENTARY NOTES <br/>
Complete data sets and key analysis codes were provided as R Data Space through the github link https://github.com/changwn/BC-CRC. Key data sets were listed below:

1)  Original Gene Expression data:<br/>
    GEO-RData
2)  CMS classes of each sample:<br/>
    CMS_sample_list_all.RData
3)  Complete sets of identified BCs with significance: <br/>
    TCGA_sig_BC_list_all_new_pp.RData, sig_BC_list_all_new_pp.RData
4)  Pathway enrichment of the BCs:<br/>
    PE_all_list.RData, TCGA_PE_all_list.RData
5)  Association with CMS classes of the BCs:<br/>
    CMS_BC_enrich_list.RData
6)  Clinical association with each BC:<br/>
    BC.CMS.clinical.RData
7)  Clinical, DFS, and OS data:<br/>
    I.gse.clinical.RData, I.gse.dfs.RData, I.gse.os.RData
8)  TCGA mutation associated BCs:<br/>
    TCGA_mutation_BC_association.RData
9)  TCGA chemo-resistance associated BCs and relevant information:<br/>
    TCGA_chemo_resistance_data.RData
