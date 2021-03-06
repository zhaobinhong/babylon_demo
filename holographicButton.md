```$xslt
onPointerClickObservable
onPointerClickObservable:可见< Vector3WithInfo >
继承自Container3D.onPointerClickObservable
(用鼠标)单击控件时触发的事件
______

onPointerDownObservable
onPointerDownObservable:可见< Vector3WithInfo >
继承自Container3D.onPointerDownObservable
指针轻击控件时触发的事件
______

onPointerEnterObservable
onPointerEnterObservable:可见< Control3D >
继承自Container3D.onPointerEnterObservable
指针进入控件时触发的事件
______

onPointerMoveObservable
onPointerMoveObservable:可见< Vector3 >
继承自Container3D.onPointerMoveObservable
指针移动到控件上时触发的事件
______

onPointerOutObservable
onPointerOutObservable:可见< Control3D >
继承自Container3D.onPointerOutObservable
指针离开控件时触发的事件
______

onPointerUpObservable
onPointerUpObservable:可见< Vector3WithInfo >
继承自Container3D.onPointerUpObservable
指针向上时触发的事件
______

parent
parent:Nullable < Container3D >
继承自Container3D.parent
获取或设置父容器
______

pointerDownAnimation
pointerDownAnimation:函数
继承自Container3D.pointerDownAnimation
用来启动指针向下的回调动画
______

pointerEnterAnimation
pointerEnterAnimation:函数
继承自Container3D.pointerEnterAnimation
用来启动指针进入动画的回调
______

pointerOutAnimation
pointerOutAnimation:函数
继承自Container3D.pointerOutAnimation
用来启动指针的回调动画
______

pointerUpAnimation
pointerUpAnimation:函数
继承自Container3D.pointerUpAnimation
用来启动指针动画的回调
______

backMaterial
get backMaterial (): FluentMaterial
获取此按钮使用的返回材料
返回FluentMaterial
______

content
get content(): Control
set content(value: Control): any

继承自Button3D.content
获取或设置用于显示按钮外观的GUI 2D内容
将控制返回
______

contentResolution
get contentResolution (): int
set contentResolution(value:int):
继承自Button3D.contentResolution
获取或设置用于渲染内容的纹理分辨率(默认为512)
返回int
______

contentScaleRatio
get contentScaleRatio():int
set contentScaleRatio(vlaue:number):
继承自Button3D.contentScaleRatio
获取或设置用于渲染内容的纹理比例(默认为2)
返回int
______

frontMaterial
get frontMaterial (): FluentMaterial
获取此按钮使用的前端材质
返回FluentMaterial
______

imageUrl
get imageUrl():String
set imageUrl(value:string):
获取或设置按钮的图像url
返回字符串
______

isVisible
get isVisible():布尔
set isVisible(value: boolean): any
继承自Container3D.isVisible
获取或设置一个布尔值，指示控件是否可见
返回布尔值
______

mesh
get mesh():Nullable < AbstractMesh >
继承自Container3D.mesh
获取用于渲染此控件的网格
返回Nullable < AbstractMesh >
______

node
get node():Nullable < TransformNode >
继承自Container3D.node
获取此控件使用的转换节点
返回Nullable < TransformNode >

______

plateMaterial
get plateMaterial (): StandardMaterial
获取此按钮使用的板材材料
返回StandardMaterial
______

position
get position():Vector3
set position(value:Vector3):any
继承自Container3D.position
获取或设置控件在世界空间中的位置
返回Vector3
______

renderingGroupId
get renderingGroupId():int
set renderingGroupId(id: number):any
渲染按钮中所有网格的ground id
返回int
______

scaling
get scaling():Vector3
set scaling(值:Vector3):任意
继承自Container3D.scaling
获取或设置世界空间中的控件缩放
返回Vector3
______

shareMaterials
get shareMaterials():Boolea
获取一个布尔值，指示此按钮是否与其他全息按钮共享其材质
返回布尔值
______
文本
text
get text(): string
set text(value: string): any
获取或设置按钮的文本
返回字符串
______

tooltipText
get tooltipText (): Nullable <字符串>
set tooltipText(text: Nullable): any
当悬停在按钮上时，将显示在工具提示上的文本。当设置为空时，工具提示被禁用。(默认值是null)
返回Nullable <字符串>
______

typeName
get typeName():字符串
继承自Container3D.typeName
获取表示类名的字符串
返回字符串
______

方法
addBehavior
addBehavior(行为:行为< Control3D >): Control3D
实现IBehaviorAware.addBehavior
继承自Container3D.addBehavior
将行为附加到控件
______



dispose
dispose():null
实现IDisposable.dispose
覆盖Button3D.dispose
释放所有相关资源
返回null
______

getBehaviorByName
getBehaviorByName(名称:字符串):Nullable <行为< Control3D > >
实现IBehaviorAware.getBehaviorByName
继承自Container3D.getBehaviorByName
按名称获取附加行为
______

参数
name:字符串
定义要查找的行为的名称
返回Nullable <行为< Control3D > >
如果在请求的行为之外没有找到行为，则为空
______

getClassName
getClassName():字符串
继承自Container3D.getClassName
获取控件的当前类名。
返回字符串 当前类名
______

linkToTransformNode
linkToTransformNode(节点:Nullable < TransformNode >): Control3D
继承自Container3D.linkToTransformNode
将控件链接为给定节点的子节点

参数
node:Nullable < TransformNode >
定义要链接的节点。使用null解除控件的链接
返回Control3D
______

removeBehavior
removeBehavior(行为:行为< Control3D >): Control3D
实现IBehaviorAware.removeBehavior
继承自Container3D.removeBehavior
删除附加行为

______
```

