# qiweiwei-work
# 网络工程和组网课程设计
##  需求分析
    1. 设计一个网络，首先要为用户分析目前面临的主要问题，确定用户对网络的真正需求，并在结合未来可能的发展要求的基础上选择、
    设计合适的网络结构和网络技术，提供用户满意的高质服务。网络在南京林业大学日常教学办公环境中起着至关重要的作用，校园网的运
    作模式会带来大量动态的www应用数据传输，会有相当一部分应用的主服务器有高速接入网络的需求目前为100/1000Mbps，今后可会更
    高。这就要求网络有足够的主干带宽和扩展能力。同时，一些新的应用类型，如网络教学、视频直播/广播等，也对网络提出了支持多点
    广播和宽带高速接入的要求。
    2. 要注意到由于逻辑上业务网和管理网必须分开，所以建成后校园网应能提供多个网段的划分和隔离，并能做到灵活
    改变配置，以适应教学办公环境的调整和变化，及实现移动教学办公的要求。按目前通常的考虑，建议数据信息点的接入以交换10/100
    Mbps自适应以太网端口接入为主，以供带宽需求较高用户或应用使用。整个方案设计的目的是建设一个集数据传输和备份、多媒体应用、
    语音传输、OA应用和Internet访问等于一体的高可靠、高性能的宽带多媒体校园网。
    3. 满足计算机教学科研、行政办公需要，提供各种教学、办公工具和支撑平台，并提供丰富的计算机软硬件系统资源。
    4.学校网络系统一定要确保整个计算机网络系统的高度可靠性、安全性，具有相当的冗余。容错能力强，确保重要及高敏信息处理的绝对
    安全保密。
    5. 宿舍：学生宿舍分为5栋楼。宿舍区学生对网络尤其是对无线网络的需求比较大，因此要确保无线网络的覆盖率。
##  可行性分析
    1.  *经济性*
    在一定的资金资源下，建立一个高水平、完善的计算机网络。为了适应系统变化的要求，必须充分考虑以最简便的方法、最
    低的投资，实现系统的扩展和维护。通常情况下，综合布线系统的使用寿命为10～15年。
    2. *可靠性*
    综合布线采用高品质的材料和组合压接的方式构成一套高标准的信息通道，每条通道都采用专用的仪器校核线路衰减、串音、
    信噪比，以保证电气的能力，因而不会造成信息的交叉干扰。另外物理拓扑星形结构的特点，使得任何一条线路故障均不影响其他线路的
    运行。
    3. *冗余性*
    在整个校园网的设备选择及综合布线中，为了方便今后的扩展，网络的核心交换机、汇聚层交换机和接入层交换机都至少留
    了三个以上的备用端口，冗余的端口为今后教学大楼进行办公室扩展都十分的方便，在综合布线的垂直主干道布线中，为了防止线路故障
    会导致整个网络瘫痪，布线中采用了两条主干道，都充分的考虑到网络冗余，为日后网络的管理与维护都提供了便利。
## 系统总体设计

这是学生公寓总体设计示意图：
![](http://m.qpic.cn/psc?/V113YiXu2vGqqA/ZOCeIbt3t.P7YdMG6dQVpCW5EBYXrl0KEaoLQqO8QbH0fvDzDfob5a0pUTuDNqNqiqP0KwkF0kOz.u2KsngT6w!!/m&bo=kQY4BAAAAAADB4k!&rf=photolist)



## 网络拓扑结构设计
   不同宿舍楼连接到相同的服务器上，各宿舍楼分别安装服务器，宿舍楼各层安装不同的交换机，每层宿舍楼使用总线型结构，每间宿舍都接入无线局域网，供不同移动终端使用。
   
   这是学生公寓各栋网络拓扑结构示意图：
   ![](http://m.qpic.cn/psc?/V113YiXu2vGqqA/ZOCeIbt3t.P7YdMG6dQVpJ2FbYn0vE9aj4WH2ch7qRQLpKUHrqx1w.6dWqLYwVoJbLsL4muZhqq5pN.CS7rdYw!!/m&bo=qAa2AwAAAAADBzk!&rf=photolist)
   
   
##物理设计（设备选型）
1. 设计标准   
    IEEE802.3 10－BASE－T  
    IEEE802.3u Ethernet(100BASE-T)   
    EIA/TIA568 EIA/TIA569EIA/TIA     
    TSB36/40工业标准及国际商务建筑布线标准   
2.设备选择    
#### 设备选择
<table>
    <td> miaoshu  </td>   
    
       


   

   
   
   


    
    
    
    
    
    
    
    
    
    
    
    
