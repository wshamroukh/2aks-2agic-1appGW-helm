# 2aks-1agic-helm
Two Azure Kubernetes Services (AKS) clusters with a shared single Application Gateway and AGIC deployed to each AKS cluster via Helm

This script gives you an idea on how to configure multiple AKS clusters where AGIC deployed via helm chart and they are all using a single shared Application Gateway.

References:
- https://github.com/Azure/application-gateway-kubernetes-ingress/blob/master/docs/setup/install-existing.md#multi-cluster--shared-app-gateway
- https://github.com/paolosalvatori/aks-multi-tenant-agic

