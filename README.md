# 🏷️ Gerador de Cartaz de Oferta

Uma ferramenta web simples e eficiente para criar cartazes promocionais profissionais em segundos. Ideal para lojas, comércios e estabelecimentos que precisam criar materiais promocionais rapidamente.

## ✨ Funcionalidades

- **Interface Intuitiva**: Formulário simples com campos para produto, preço e unidade
- **Templates Variados**: 6 templates diferentes para diferentes tipos de promoção
- **Visualização em Tempo Real**: Veja o cartaz sendo criado conforme você digita
- **Impressão Otimizada**: Geração de PDF para impressão em tamanho A4
- **Design Responsivo**: Funciona perfeitamente em desktop e mobile
- **Formatação Automática**: Formatação automática de preços e textos

## 🎨 Templates Disponíveis

1. **Padrão** - Fundo amarelo com cabeçalho vermelho
2. **Black Friday** - Design escuro com efeitos neon
3. **Liquidação** - Vermelho vibrante para promoções especiais
4. **Feirão** - Verde com detalhes amarelos
5. **Promoção Relâmpago** - Laranja chamativo
6. **Laranja Listrado** - Design moderno com padrão listrado

## 🚀 Como Usar

1. **Preencha os Campos**:
   - Nome do produto
   - Preço (formato: 199,90)
   - Unidade de medida (ex: PAR, KG, UN)

2. **Escolha um Template**: Clique em um dos botões de template

3. **Gere o Cartaz**: Clique em "GERAR CARTAZ"

4. **Imprima**: Use o botão "IMPRIMIR COMO PDF" para salvar ou imprimir

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da aplicação
- **CSS3** - Estilos e animações
- **JavaScript** - Funcionalidades interativas
- **Tailwind CSS** - Framework CSS para estilização
- **Google Fonts** - Tipografia (Roboto)
- **html2canvas** - Geração de imagens (se necessário)

```

## 🎯 Características Técnicas

- **Responsivo**: Adapta-se a diferentes tamanhos de tela
- **Otimizado para Impressão**: CSS específico para impressão em A4
- **Validação de Dados**: Verificação automática dos campos obrigatórios
- **Formatação Inteligente**: Formatação automática de preços e textos
- **Performance**: Carregamento rápido sem dependências pesadas

## 📋 Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet (para carregar fonts e CDNs)
- JavaScript habilitado

## 🔧 Instalação e Uso

1. **Clone o repositório**:
```bash
git clone https://github.com/seu-usuario/gerador-cartaz-oferta.git
```

2. **Navegue até o diretório**:
```bash
cd gerador-cartaz-oferta
```

3. **Abra o arquivo**:
```bash
# Abra o index.html no seu navegador
# Ou use um servidor local como Live Server (VS Code)
```

4. **Ou acesse diretamente**: Abra o arquivo `index.html` em qualquer navegador

## 💡 Dicas de Uso

- **Produtos com Nomes Longos**: O sistema ajusta automaticamente o tamanho da fonte
- **Preços**: Use vírgula como separador decimal (ex: 129,90)
- **Unidades**: Seja específico (PAR, KG, LITRO, UNIDADE)
- **Impressão**: Para melhor qualidade, use papel A4 e impressora colorida

## 🎨 Personalização

O código é facilmente personalizável. Você pode:

- Adicionar novos templates no JavaScript
- Modificar cores e estilos no CSS
- Ajustar tamanhos de fonte
- Criar novos layouts

### Exemplo de Novo Template:

```javascript
case 'meutemplate':
  cartaz.classList.add('bg-blue-500', 'border-blue-600');
  cabecalho.classList.add('bg-white', 'text-blue-600');
  cabecalho.textContent = 'MEU TEMPLATE';
  // ... mais configurações
  break;
```

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

**Zenilson Araújo de Sousa Lacerda**

- Email: zenilsonaraujo@gmail.com

## 🙏 Agradecimentos

- [Tailwind CSS](https://tailwindcss.com/) - Framework CSS
- [Google Fonts](https://fonts.google.com/) - Tipografia
- [html2canvas](https://html2canvas.hertzen.com/) - Captura de tela

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no GitHub!
