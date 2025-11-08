# Repositório de Laboratórios Google Cloud Platform

Este repositório contém scripts de automação, arquivos de configuração e código de Infraestrutura como Código (IaC) desenvolvidos durante a realização de vários laboratórios práticos na Google Cloud Platform (GCP).

## Estrutura de Pastas

Os projetos estão organizados por temas:

* **`01-Networking-And-LoadBalancing/`**: Configurações de VPC, Firewall, VPNs e balanceadores de carga.
* **`02-Compute-And-AppDev/`**: Configuração de VMs, GKE e ambientes de desenvolvimento de aplicações.
* **`03-Security-And-IAM/`**: Gerenciamento de Identidade e Acesso (IAM) e fundamentos de segurança.
* **`04-Infrastructure-as-Code/`**: Projetos usando Terraform para provisionamento de infraestrutura.

## Executando um Script no Cloud Shell

Para executar um script diretamente no Google Cloud Shell, use o seguinte padrão (substitua o caminho e o nome do arquivo, e certifique-se de que o repositório está público):

```bash
# 1. Baixe o script
curl -LO https://raw.githubusercontent.com/wesleysampa/gcp/main/caminho/para/seu/script.sh

# 2. Adicione permissão de execução
chmod +x script.sh

# 3. Execute o script
./script.sh