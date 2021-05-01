# TODO

- [(bug) Apply LXD VMs in parallel](../infra/Makefile#L12)
- [(bug) Investigate why --noconfirm is not working](../tools/Dockerfile#L3)
- [(bug) Should be posible to put it in the profile instead lxd_profile.kubenode.config, and make it a variable](../infra/cluster.tf#L100)
- [(feature) Automatic ingress and tunnel for all services](../infra/modules/kubernetes-cluster-bootstrap/main.tf#L85)
- [(feature) Enable etcd authentication and generate terraform backend config variables](../metal/roles/tfstate/tasks/main.yml#L43)
- [(feature) Generate endpoint automatically (terragrunt for variable)](../infra/terraform.tf#L2)
- [(feature) Upgrade hosts kernel to use Wireguard in container](../infra/modules/vpn/main.tf#L15)
- [(optimize) Change to /var/lib/lxd/server.crt after https](../metal/roles/lxd/tasks/main.yml#L26)
- [(optimize) Convert to YAML for Terraform yamldecode](../metal/hosts.ini#L1)
- [(optimize) Decide if VPN should be inside Kubernetes](../infra/vpn.tf#L1)
- [(optimize) DRY master and worker definition](../infra/cluster.tf#L89)
- [(optimize) HA Vault and auto unseal Vault](../infra/modules/kubernetes-cluster-bootstrap/main.tf#L82)
- [(optimize) LXD node firewall](../metal/roles/lxd/tasks/main.yml#L6)
- [(optimize) LXD node SELinux](../metal/roles/lxd/tasks/main.yml#L1)
- [(optimize) Make parent interface a variable](../infra/modules/vpn/main.tf#L38)
- [(optimize) Use btrfs in k8s 1.19.8 https](../metal/roles/lxd/templates/leader.yaml.j2#L17)
- [(optimize) Use metal values for MetalLB values](../infra/modules/kubernetes-cluster-bootstrap/values/metallb.yaml#L6)
- [(optimize) Use template for tfvars](../metal/roles/lxd/tasks/main.yml#L38)