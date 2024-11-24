# Homelab

I'd like to manage as much homelab infra and config with IaC / version
control. Yet with also still understanding what everyting is doing.
Therefore, here's a posibility:

1. manually create a VM from which to manage everything (done)
1. set up local TF for configuring the github runners for next step
1. set up gitops TF and Ansible pipeline
1. use Terraform to provision proxmox VMs for the k8s cluster
1. use Ansible / kubeadm to install the k8s cluster
1. cloudflare tunnel to publicly expose the k8s cluster, maybe with TF?
1. Terraform to manage cloudflare DNS
