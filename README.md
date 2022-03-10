
### 使用kubebuilder构建Kubenetes Operator

##### 需要实现业务逻辑的一些文件
api/v1beta1/mydaemonset_types.go 

api/v1beta1/mydaemonset_webhook.go 

config/default/kustomization.yaml 

config/samples/apps_v1beta1_mydaemonset.yaml 

controllers/mydaemonset_controller.go 

