# Mask2FormerOneFile
Simple Implement Mask2Former in One File !



## NOTE
This code is different from original's implement

- use SimpleFPN module generate multi scale feature maps

- use Conv layer implement PixelDecoder rather than DeformableAttn


## Why written this

Recently, I began delving into the realm of instance segmentation and encountered Mask2Former, which end2end structure is very elegant, but both original repo [Mask2Former](https://github.com/facebookresearch/Mask2Former) and [mmdet](https://github.com/open-mmlab/mmdetection) to be quite complex and challenging to understand.

My code is inspired by the original repository and mmdet's implementation and wish this work will help more and more end2end structure detect model come out.