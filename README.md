# cilium-notes
```sh
kind create cluster
cilium install
cilium status --wait
kubectl create -f https://raw.githubusercontent.com/cilium/cilium/1.14.4/examples/minikube/http-sw-app.yaml
```
