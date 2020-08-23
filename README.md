# Local-aware-Spatio-temporal-Attention-Network-with-Multi-stage-Feature-Fusion-for-Human-Action-Recog
datasets:You can download the RGB and Optical Flow frames for both UCF-101 and HMDB-51 at the official repository at https://github.com/feichtenhofer/st-resnet#models-st-mulnet. 
introduction
  we propose a local-aware spatio-temporal attention network with multi-stage feature fusion for video-level human action recognition; this network is trainable in an end-to-end manner.
  First, to capture the meaningful regions about human actions from video frames, we utilize multiple STNs (5×STNs) to locate the attentional regions of the human body, and then we 
  perform feature fusion between the local and global features to enhance the human action representation with the accuracy of 87.5%. The experimental results demonstrate that the 
  presented attention model can significantly improve the recognition performance of our proposed architecture. Moreover, we employ multi-stage feature fusion by compact bilinear pooling 
  withthe dimensionality of the 4096-d vector to learn the feature correspondences at the pixel level between the spatial and temporal streams and reported an accuracy of 93.1%. Next, 
  we present ablation studies to test the individual effectiveness of each feature fusion. The obtained results highlight the superiority of our approach compared with other feature fusion 
  methods, i.e., sum, conv, and concatenation. Finally, with an accuracy rate of 95.3% on UCF101 and 72.9% on HMDB51, we can conclude that our proposed architecture meets our expected 
  results and achieves state-of-the-art performance.
