# Upload.ai

![Captura de tela 2023-09-20 211706](https://github.com/wesleivisentin/Upload-AI/assets/78518664/820ba6e5-49f4-4402-bed4-d70fdd6235f8)



![Captura de tela 2023-09-20 212225](https://github.com/wesleivisentin/Upload-AI/assets/78518664/7a97a606-576a-44b6-895a-c8fc3d53d962)


## Descrição

O **Upload.ai** é uma ferramenta poderosa para simplificar o processo de criação de conteúdo para o YouTube. Combinando uma série de tecnologias avançadas, este projeto permite que você faça o seguinte:

 **Criação Automatizada de Títulos e Descrições para o YouTube:** A partir das transcrições geradas, este projeto utiliza a API do Chat GPT para criar automaticamente títulos atrativos e descrições envolventes para seus vídeos do YouTube. Isso não só economiza tempo, mas também ajuda a melhorar a visibilidade e o engajamento de seu conteúdo.

## Tecnologias Utilizadas

Este projeto foi desenvolvido com um conjunto de tecnologias modernas, incluindo:

- **`React`:** Uma biblioteca JavaScript popular para construção de interfaces de usuário interativas e reativas.

- **`TypeScript`:** Uma linguagem de programação que adiciona tipagem estática ao JavaScript, tornando-o mais seguro e fácil de manter.

- **`Tailwind CSS`:** Um framework de CSS utilitário que simplifica a criação de designs bonitos e responsivos.

- **`Axios`:** Uma biblioteca para fazer requisições HTTP no navegador e no Node.js.

- **`Vite`:** Um bundler e servidor de desenvolvimento rápido para projetos front-end.

- **`FFmpeg`:** Uma biblioteca e conjunto de ferramentas para manipulação de áudio e vídeo.

- **`Radix UI`:** Um conjunto de componentes de interface de usuário acessíveis e flexíveis.

- **`PostCSS`:** Um processador de CSS com plugins poderosos para otimização e transformação de estilos.

- **`Node.js`:** Um ambiente de execução JavaScript de servidor confiável e eficiente.

- **`Fastify`:** Um framework web rápido e de baixa sobrecarga para Node.js.

- **`Prisma`:** Uma camada de acesso a dados moderna e segura para aplicativos Node.js e TypeScript.

- **`Dotenv`:** Uma ferramenta para carregar variáveis de ambiente de um arquivo `.env`.

- **`OpenAI`:** A API do Chat GPT é usada para gerar títulos e descrições atraentes para seus vídeos.

- **`Zod`:** Uma biblioteca de validação de esquemas TypeScript.

## Como Usar

certifique-se de ter o Node.js e o npm instalados antes de prosseguir com as etapas abaixo:

## Na pasta upload-ai-api
Instale as dependências:
```
$ npm install
```
Execute as migrações:
```
$ npx prisma migrate dev
```
Inicie o servidor:
```
$ npm run dev
```
## Na pasta upload-ai-web
Instale as dependências:
```
$ npm install
```
Inicie o servidor:
```
$ npm run dev
```

⚠️ Importante: Crie um arquivo .env de acordo com o arquivo .env.example. No campo DATABASE_URL, especifique a URL do banco de dados que deseja utilizar. Crie uma conta no site OpenAI, obtenha sua chave da API e preencha o campo OPENAI_KEY com sua chave.







![GitHub Stars](https://img.shields.io/github/stars/wesleivisentin/Upload-AI?style=social)
![GitHub Forks](https://img.shields.io/github/forks/wesleivisentin/Upload-AI?style=social)

