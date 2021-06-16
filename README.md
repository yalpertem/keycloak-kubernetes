```
kubectl apply -f simple-keycloak-deployment.yaml 
kubectl apply -f simple-keycloak-node-port.yaml 
kubectl apply -f simple-keycloak-ingress.yaml 
```
Then visit http://192.168.49.2:32607/ where the ip = `minikube ip`
