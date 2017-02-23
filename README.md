# ansible-kubernetes

The set of Ansible playbooks used to install Kubernetes on the cluster behind [Weave Cloud](https://cloud.weave.works).  Features include:
- Epheremal disk management with LVM
- Tweaked log rotation
- Docker installation and configuration
- Kubelet installation and configuration
- Static Pod configurations for a multi-master HA Kubernetes setup
- Kubernetes Minion configuration

NB this will not provision the VMs etc for the Kubernetes cluster, just install Kubernetes on existing VMs.  For VM provisioning, see [terraform-kubernetes](https://github.com/weaveworks/terraform-kubernetes.git).

See ["Provisioning and Lifecycle of a Production Ready Kubernetes Cluster"](https://www.weave.works/provisioning-lifecycle-production-ready-kubernetes-cluster/) for more info.
