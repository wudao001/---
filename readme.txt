����˵��

��Ҫ��װ��
python ==3.6
torch ==1.3.1
torchvision == 0.4.2

Davis���ݼ���ַ��https://davischallenge.org/index.html��

LSMVOS�ж�ʱƥ��ģ���õ���Flownet2�еĻ�������㣬��Ҫ��װpytorch��һ��ʵ�֣�https://github.com/NVIDIA/flownet2-pytorch/tree/master/networks/correlation_package��
�����ѵ���Ļ����밲װCorrelationģ�飬������ԵĻ�����ʹ�ñ���ʵ�֣�����ʵ�ֻὫͼƬ�ֳɼ��飬���Ը����Դ��С������

ָ�
python evaluation.py --deviceID 0 1 --Using_Correlation False --scale 10 --batch_size 1 --year '2016' --mode 'val' --path 'LSMVOS_DAVIS_2016.pth' --root '/home/rv/Desktop/DAVIS'

deviceID: ָGPUid��Ĭ��Ϊ0
Using_Correlation: �Ƿ�װ��Correlationģ��
scale: ͼƬ�������أ�Ĭ�ϰ���10����Ϊ1��
batch_size: ������С��Ĭ��Ϊ1
year: Davis���ݼ���ݣ�Ĭ��Ϊ'2016'
mode: Davis���ݼ����Ĭ��Ϊ'val'
path: 'ģ�Ͳ�����ַ'
root: '���ݼ���ַ'