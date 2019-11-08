# Thundernet_Pytorch

## Requirements
* pytorch 1.2.0
* torchvision 0.4


## Update 
### 20191108

## Lib Prepare 
```sh
git clone 
```
### Build PSROIAlign layer
```sh
cd versions/psroialign/PSROIAlign && sh build.sh 
 ```   
## Data Prepare 
Download VOC0712 datasets 
Then cd datapre run  voc2txt.py (I have do it )


## Train
```sh
python3 Train_thundenet.py
```

## Test
```sh
python3 Testing.py
```

## Citation
Please cite the paper in your publications if it helps your research:
```
@article{zheng2019thundernet,
  title={ThunderNet: Towards Real-time Generic Object Detection},
  author={Zheng Qin, Zeming Li,Zhaoning Zhang,Yiping Bao,Gang Yu, Yuxing Peng, Jian Sun},
  journal={arXiv preprint arXiv:1903.11752},
  year={2019}
}
```





