- Create secret

``` bash
kubectl create secret tls aliyun-k8s-ingress-tls \
--key cert/config/archive/yogiman.cn/privkey1.pem \
--cert cert/config/archive/yogiman.cn/fullchain1.pem
```