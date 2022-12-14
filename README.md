# Nerf(神经辐射场)学习笔记

>本人的科研方向是三维重建与对抗生成，Nerf让人惊叹

### 一. 基本原理
>争取搞清楚每一个数学公式和每一行代码
01. [颠覆传统三维重建方法之nerf(一)---概述](01.颠覆传统三维重建方法之nerf(一)---概述.md)
02. [颠覆传统三维重建方法之nerf(二)---工作流程与基本原理](02.颠覆传统三维重建方法之nerf(二)---工作流程与基本原理.md)

后面的还没有整理
03. [颠覆传统三维重建方法之nerf(三)---公式推导前准备之光线的表示与采样](03.颠覆传统三维重建方法之nerf(三)---公式推导前准备之光线的表示与采样.md)
03. [颠覆传统三维重建方法之nerf(四)---公式推导-光线成像模型](04.颠覆传统三维重建方法之nerf(四)---公式推导-光线成像模型.md)
04. [颠覆传统三维重建方法之nerf(四)---pytorch-nerf项目介绍](04.颠覆传统三维重建方法之nerf(四)---pytorch-nerf项目介绍.md)
05. [颠覆传统三维重建方法之nerf(五)---复习相机几何与相机参数](05.颠覆传统三维重建方法之nerf(五)---复习相机几何与相机参数.md)
06. [颠覆传统三维重建方法之nerf(六)---pytorch-nerf数据格式与数据加载](06.颠覆传统三维重建方法之nerf(六)---pytorch-nerf数据格式与数据加载.md)
07. [颠覆传统三维重建方法之nerf(七)---pytorch-nerf模型创建1之概述](07.颠覆传统三维重建方法之nerf(七)---pytorch-nerf模型创建1之概述.md)
08. [颠覆传统三维重建方法之nerf(八)---pytorch-nerf模型创建2之位置编码](08.颠覆传统三维重建方法之nerf(八)---pytorch-nerf模型创建2之位置编码.md)
09. [颠覆传统三维重建方法之nerf(九)---pytorch-nerf模型创建3之创建NeRF](09.颠覆传统三维重建方法之nerf(九)---pytorch-nerf模型创建3之创建NeRF.md)
10. [颠覆传统三维重建方法之nerf(十)---pytorch-nerf模型训练1之概述](10.颠覆传统三维重建方法之nerf(十)---pytorch-nerf模型训练1之概述.md)
11. [颠覆传统三维重建方法之nerf(十一)---pytorch-nerf模型训练2之计算光线](11.颠覆传统三维重建方法之nerf(十一)---pytorch-nerf模型训练2之计算光线.md)
12. [颠覆传统三维重建方法之nerf(十二)---pytorch-nerf模型训练3之渲染(光线成像)](12.颠覆传统三维重建方法之nerf(十二)---pytorch-nerf模型训练3之渲染(光线成像).md)
13. [颠覆传统三维重建方法之nerf(十三)---pytorch-nerf模型训练4之损失函数](13.颠覆传统三维重建方法之nerf(十三)---pytorch-nerf模型训练4之损失函数.md)
14. [颠覆传统三维重建方法之nerf(十四)---pytorch-nerf模型测试与推理](14.颠覆传统三维重建方法之nerf(十四)---pytorch-nerf模型测试与推理.md)
15. [颠覆传统三维重建方法之nerf(十五)---pytorch-nerf总结](15.颠覆传统三维重建方法之nerf(十五)---pytorch-nerf总结.md)

### 二. 读[instant-ngp](https://github.com/NVlabs/instant-ngp) 源码系列
1. [下载编译运行ngp](instant-ngp/1.下载编译运行ngp.md)

### 三. 读[ngp_pl](https://github.com/kwea123/ngp_pl) 源码系列

### 四. 各种应用场景及其模型


#### NeuMan
1. [NeuMan](NeuMan/NeuMan.md)：基于Nerf的从单个视频实现人体三维重建。
2. [NeuMan-预处理](NeuMan/NeuMan-预处理.md)

#### AD-NeRF 
由音频和人脸图像合成人脸视频并表现出自然的说话风格
https://yudongguo.github.io/ADNeRF/
https://github.com/YudongGuo/AD-NeRF

#### 4D-Facial-Avatars：
https://github.com/gafniguy/4D-Facial-Avatars

#### NeRFFaceEditing：
http://geometrylearning.com/NeRFFaceEditing/
https://mp.weixin.qq.com/s/cv6g-5i9C5ej2CQtI0tEGw

#### FENeRF
使用 NeRF 进行人脸编辑
https://mrtornado24.github.io/FENeRF/
https://mp.weixin.qq.com/s/G6b9M3PrMjhwRWLJw6GmpQ

#### KeypointNeRF：基于图像的体积化身的泛化

#### StyleNeRF

#### PixelNeRF

#### IBRNet

#### CLIP-NeRF 文字-图像驱动的 NeRF 操作
https://mp.weixin.qq.com/s/DDt6rVGk4inBFkDnlgBpQA

#### AdaNeRF：自适应采样用于神经辐射场实时渲染
https://mp.weixin.qq.com/s/XJTrg-iAOC8PQLjsnmL1oQ

#### MoFaNeRF: 可变形面部神经辐射场
https://mp.weixin.qq.com/s/Wmx6l3IDOBV8PH1taka71w

#### 在 StyleGAN 中注入可控三维感知 NeRF-GAN 用于可编辑人像合成
https://mp.weixin.qq.com/s/QcLsHTKEEgB53Z0oi7kaPA

### [更多](https://github.com/yenchenlin/awesome-NeRF)

### 四. 各种参考资料/课程/视频


