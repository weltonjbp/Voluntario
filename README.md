Documento de Usabilidade Proposta do Site
Scanner de Folhas de Presença
1. Objetivo do Site
O site tem como objetivo facilitar o envio digital de folhas de presença, permitindo ao usuário:

Cadastrar informações da Casa de Oração, mês/ano de competência e período de dias.
Adicionar múltiplos "Livros" (categorias de folhas).
Anexar imagens das folhas, via upload ou captura direta da câmera.
Gerar um arquivo PDF único contendo todas as folhas, pronto para ser compartilhado ou baixado, promovendo organização, centralização e praticidade no envio dessas informações.
2. Fluxo Básico de Uso
Acesso ao formulário: O usuário vê um formulário centralizado no site, com campos claros e instruções de destaque (alerta para ignorar folhas amarelas/carbono).
Preenchimento dos dados gerais: Preenche os campos obrigatórios:
Casa de Oração (texto)
Ano/Mês de Competência (seletor de mês)
Período de Dias (texto)
Inclusão de Livros: O usuário pode:
Informar o nome do livro.
Adicionar imagens (via upload de arquivos ou câmera do dispositivo).
Adicionar quantos livros forem necessários, com o botão “Adicionar Livro”.
Adição de Imagens
Upload: Seleciona múltiplas imagens do dispositivo.
Câmera: Abre modal para captura de foto(s) usando a câmera do dispositivo, com pré-visualização e confirmação das imagens.
Pré-visualização: O usuário vê miniaturas das imagens carregadas, por livro, facilitando conferência antes do envio.
Geração do PDF: Ao clicar em “Gerar PDF e Enviar”:
As imagens de todos os livros são organizadas e agrupadas em um PDF.
O arquivo pode ser compartilhado via Web Share API (em navegadores suportados) ou baixado automaticamente.
Mensagem de carregamento é exibida durante o processamento.
3. Elementos de Usabilidade Implementados
Layout e Organização:
Centralização do conteúdo e containers para fácil leitura.
Responsividade para telas grandes e pequenas.
Separação visual entre seções (alerta, formulário, pré-visualização).
Acessibilidade:
Rótulos (label) claros e alinhados aos inputs.
Botões grandes e bem identificados.
Alerta visual destacado com cor e ícone para instruções importantes.
Facilidade de Uso:
Campos obrigatórios com validação.
Botão de adicionar livros permite flexibilidade.
Uploads múltiplos em cada livro.
Captura por câmera integrada, com fallback.
Pré-visualização imediata das imagens.
Modal de câmera com confirmação/cancelamento e feedback visual.
Feedback ao Usuário:
Indicador de carregamento durante a geração do PDF.
Mensagens de erro/alerta para campos obrigatórios e problemas de câmera.
Confirmação visual das imagens capturadas e carregadas.
Compatibilidade e Acessibilidade Progressiva:
Web Share API utilizada quando disponível para compartilhamento direto do PDF.
Fallback para download automático se não suportado.
Uso de jsPDF garante portabilidade do PDF.
4. Destaques Diferenciais
Processo todo digital: da captura das folhas até o envio, sem aplicativos externos.
Apoio a dispositivos móveis: uso da câmera do smartphone para agilidade.
Multi-categorias: separação por “Livro”.
Orientações claras: reduz erros de envio.
Geração automatizada de PDF: elimina etapas manuais e padroniza envios.
5. Conclusão
O site propõe uma solução eficiente, intuitiva e moderna para digitalização e envio de folhas de presença, com foco na usabilidade para usuários não técnicos, principalmente em dispositivos móveis. O fluxo é pensado para minimizar erros, reduzir atritos e acelerar o processo de envio, com interface amigável e recursos de feedback visual constantes, promovendo uma experiência segura e produtiva.
