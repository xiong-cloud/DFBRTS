# DFBRTS
Codes of DFBRTS

Enhancing Motor Imagery Decoding in Brain–Computer Interfaces using Riemann Tangent Space Mapping and Cross Frequency Coupling

Objective: Motor Imagery (MI) serves as a crucial experimental paradigm within the realm of Brain-Computer Interfaces (BCIs), aiming to decoding motor intentions from electroencephalogram (EEG) signals. However, achieving accuracy of MI decoding remains a challenging endeavor due to constraints stemming from data limitations, noise, and non-stationarity. Method: Drawing inspiration from Riemannian geometry and Cross-Frequency Coupling (CFC), this paper introduces a novel approach termed “Riemann Tangent Space Mapping using Dichotomous Filter Bank with Convolutional Neural Network” (DFBRTS) to enhance the representation quality and decoding capability pertaining to MI features. DFBRTS first initiates the process by meticulously filtering EEG signals through a Dichotomous Filter Bank, structured in the fashion of a complete binary tree. Subsequently, it employs Riemann Tangent Space Mapping to extract salient EEG signal features within each sub-band. Finally, a lightweight convolutional neural network is employed for further feature extraction and classification, operating under the joint supervision of cross-entropy and center loss. To validate the efficacy, extensive experiments were conducted using DFBRTS on two well-established benchmark datasets: the BCI competition IV 2a (BCIC-IV-2a) dataset and the OpenBMI dataset. The performance of DFBRTS was benchmarked against several state-of-the-art MI decoding methods, alongside other Riemannian geometry-based MI decoding approaches. Results: DFBRTS significantly outperforms other MI decoding algorithms on both datasets, achieving a remarkable classification accuracy of 78.16% for four-class and 71.58% for two-class hold-out classification, as compared to the existing benchmarks. Conclusion: This paper serves as a testament to the effectiveness and ascendancy of DFBRTS for the realm of MI decoding, highlighting its potential to revolutionize the landscape of more robust MI-BCI applications. Significance: The findings is underscored by the effectiveness of DFBRTS in advancing the capabilities of MI-BCI applications, promising enhanced interfaces catering to individuals with motor disabilities.
