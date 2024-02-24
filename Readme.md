# Creating Namespace
kubectl create ns nginx

# Switching context

kubectl config set-context --current --namespace=traefik

# Upgrading the CRDs 

kubectl apply -f https://raw.githubusercontent.com/nginxinc/kubernetes-ingress/v3.4.3/deploy/crds.yaml

# install using helm

helm install nginx oci://ghcr.io/nginxinc/charts/nginx-ingress --version 1.1.3# nginx-setup
