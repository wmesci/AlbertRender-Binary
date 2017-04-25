AlbertRender
============

特点：
* 基于ImGUI的界面系统，方便的场景编辑、材质编辑功能
* 内置C++反射/序列化/反序列化支持
* 支持过程式纹理、层级组合式纹理
* 类似Unity中的基于组件的构架
* 支持 .fbx .obj .3ds .dae .ase 等常见的3D模型格式，支持 .vox .vol 两种体素文件格式
* 可以基于输入的函数表达式创建模型及体积散射区域
* 支持蒙皮骨骼动画
* 实时预览&编辑状态：
  使用D3D11 + 延迟渲染 + 基于物理的shader + ShadowMap + 环境光照明/基于图像的照明(IBL) + SSR + SSAO + HDR + FXAA/TXAA
* 离线渲染：
  目前支持环境遮挡渲染、光线追踪渲染、路径追踪渲染，支持各种不同的BSDF 及其组合，支持法线贴图、景深、面光源/软阴影、KD-Tree加速以及体积散射区域渲染
* BSDF重要性采样、多重重要性采样
* 支持64位

![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image.png "实时预览")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image0.png "实时预览")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image1.png "")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image2.png "")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image3.png "")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image4.png "")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image5.png "")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image6.png "")

