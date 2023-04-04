Como clonar um repositório via git bash:

1) Criar um repositório manualmente no github.
2) Copiar o link da barra de endereços.
3) Abrir o Git Bash instalado na máquina.
4) Navegar utilizando os comandos cd e dir (caso necessário) para encontrar a pasta desejada para ser clonada.
5) Utilizar o comando git init para iniciar o processo.
6) git add nome_arquivo.extensao
7) git status (para ver se tem algum item com atualizações)
8) git commit -m "Escreva aqui um comentário sobre o commit"
9) git add remote origin https://github.com/williamdahlke/testeAutomatizadoPython.git
10) git push


Como baixar os arquivos de um repositório:

1) Navegar com cd :/
2) Rodar o comando: git clone https://github.com/williamdahlke/EstudosGit.git


Como visualizar os commits que foram realizados no meu repositório:

Opção 1: git log
Opção 2: git log --oneline


Como baixar os arquivos atualizados de um repositório (caso que já tenho uma pasta que faz referência ao meu repositório):
git pull https://github.com/williamdahlke/EstudosGit.git

como voltar o meu código para um determinado commit:

git restore --source codigo_commit nome_arquivo_restaurar
git push
