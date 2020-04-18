# SGM-CNN
**A flow-based network intrusion detection model that integrates class imbalance processing with deep learning: SGM-CNN.**

###### Copyright: Lulu Huang, and Hongpo Zhang(School of Information Engineering, Zhengzhou University)

###### The two contributors of this NIDS are Ms. Lulu Huang and SN ENGR. Hongpo Zhang (zhp@zzu.edu.cn). If you have any problems, please do not hesitate to send us an email. 

 
Please cite our papers, in case you find our work useful.

 (1) Hongpo Zhang, Lulu Huang, Chase Q. Wu and Zhanbo Li:
	 An Effective Convolutional Neural Network Based on SMOTE and Gaussian Mixture Model for Intrusion Detection in Imbalanced Dataset. Computer Networks (Revision), 2020

 (2) Hongpo Zhang, Chase Q. Wu, Shan Gao, Zongmin Wang, Yuxiao Xu and Yongpeng Liu:
     An effective deep learning based scheme for network intrusion detection, in: 2018 24th International Conference on Pattern Recognition (ICPR), 2018, pp. 682–687. doi:10.1109/ICPR.2018.8546162.

In the following, we also provide a brief user manual for this NIDS.

# (1) Installation

anaconda3-5.2.0; tensorflow; python3.6; Kreas 2.2.4

# (2) Dataset

The UNSW-NB15 dataset used to support the findings of
this study is available at https://www.unsw.adfa.edu.au/unswcanberra-cyber/cybersecurity/ADFA-NB15-Datasets/.
The CICIDS2017 dataset used to support the findings of this study is available at https://www.unb.ca/cic/datasets/ids-2017.html.

# (3) NIDS execution process

1. Data preprocessing and feature selection. Different datasets have slightly different data preprocessing processes.
2. Imbalance processing. Contains five types of imbalanced processing technologies, namely ROS, SMOTE, ADASYN, RUS + SMOTE,K-means + SMOTE and SGM. 
3. Classification decision. Contains three classification algorithms, namely RF, MLP and CNN.
