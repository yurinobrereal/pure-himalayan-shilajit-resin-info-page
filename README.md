# Pure Himalayan Shilajit Resin - Página Informativa para Shopify

Este projeto contém o clone da página do produto Pure Himalayan Shilajit Resin convertido para uma página informativa em Liquid para uso no Shopify, sem funcionalidades de e-commerce.

## 📁 Arquivos Criados

### 1. `templates/page.informative.liquid`
- **Propósito**: Template personalizado para páginas informativas
- **Uso**: Assign este template a uma página no admin do Shopify

### 2. `sections/informative-content.liquid`
- **Propósito**: Seção principal com todo o conteúdo da página
- **Conteúdo**: HTML/Liquid com todas as informações do produto original

### 3. `assets/informative-style.css`
- **Propósito**: Estilos CSS modernos e responsivos
- **Design**: Layout limpo com tipografia moderna, sem ícones externos

### 4. `demo.html`
- **Propósito**: Arquivo de demonstração para testar o layout
- **Uso**: Apenas para visualização e testes

## 🚀 Como Implementar no Shopify

### Passo 1: Upload dos Arquivos
1. Acesse o admin do Shopify
2. Vá para **Online Store > Themes > Actions > Edit Code**
3. Faça upload dos arquivos nas respectivas pastas:
   - `templates/page.informative.liquid` → pasta **templates**
   - `sections/informative-content.liquid` → pasta **sections**
   - `assets/informative-style.css` → pasta **assets**

### Passo 2: Criar a Página
1. No admin do Shopify, vá para **Online Store > Pages**
2. Clique em **Add page**
3. Adicione o título: "Pure Himalayan Shilajit Resin - Informações"
4. Na seção **Search engine listing preview**, clique em **Edit website SEO**
5. No campo **Template**, selecione **page.informative**
6. Salve a página

### Passo 3: Verificar o CSS
1. Certifique-se de que o arquivo CSS está sendo carregado
2. Se necessário, adicione esta linha no `layout/theme.liquid`:
```liquid
{{ 'informative-style.css' | asset_url | stylesheet_tag }}
```

## 🎨 Características do Design

### Layout Responsivo
- Design mobile-first
- Breakpoints para tablet e desktop
- Grid system flexível

### Tipografia Moderna
- Fonte: Helvetica Neue, Arial, sans-serif
- Hierarquia clara de títulos
- Espaçamento adequado

### Esquema de Cores
- **Primária**: #2c2c2c (texto principal)
- **Destaque**: #d4af37 (dourado para marca)
- **Secundária**: #666 (texto secundário)
- **Fundo**: #fff (branco)

### Seções Incluídas
1. **Header** - Logo e navegação
2. **Produto Principal** - Imagens, título, avaliações, preços
3. **Bundles** - Opções de compra (apenas informativo)
4. **Sobre o Produto** - Benefícios detalhados
5. **Avaliações** - Depoimentos de clientes
6. **Comparação** - Biyode vs Others
7. **Resultados** - Estatísticas e certificações
8. **Especialistas** - Opinião de nutricionista
9. **Produtos Relacionados** - Sugestões
10. **Footer** - Contato e links úteis

## 🔧 Personalização

### Alterando Conteúdo
- Edite o arquivo `sections/informative-content.liquid`
- Use variáveis Liquid para conteúdo dinâmico
- Adicione metafields se necessário

### Modificando Estilos
- Edite o arquivo `assets/informative-style.css`
- Mantenha a estrutura responsiva
- Use as variáveis de cor existentes

### Adicionando Imagens
- Faça upload das imagens para **Settings > Files**
- Substitua os placeholders pelos URLs reais
- Use o filtro `| asset_url` para imagens locais

## 📱 Responsividade

### Mobile (< 768px)
- Layout em coluna única
- Navegação simplificada
- Imagens otimizadas

### Tablet (768px - 1024px)
- Layout híbrido
- Grid adaptativo
- Tipografia ajustada

### Desktop (> 1024px)
- Layout completo em duas colunas
- Todas as funcionalidades visíveis
- Espaçamento otimizado

## ⚠️ Importante

### Funcionalidades Removidas
- **Add to Cart** - Removido completamente
- **Buy Now** - Removido completamente
- **Checkout** - Não há funcionalidade de compra
- **Carrinho** - Apenas visual, sem funcionalidade

### Funcionalidades Mantidas
- **Informações do Produto** - Completas
- **Avaliações** - Apenas exibição
- **Depoimentos** - Informativos
- **Especificações** - Detalhadas

## 🎯 Objetivo

Esta implementação transforma a página de produto em uma página puramente informativa, ideal para:
- Blog posts sobre o produto
- Páginas educativas
- Conteúdo de marketing
- Informações detalhadas sem venda direta

## 📞 Suporte

Para dúvidas sobre a implementação:
1. Verifique se todos os arquivos foram uploadados corretamente
2. Confirme que o template foi assignado à página
3. Teste em diferentes dispositivos
4. Valide o CSS no navegador

## 🔄 Atualizações Futuras

Para manter o conteúdo atualizado:
1. Edite o arquivo Liquid conforme necessário
2. Adicione novas seções seguindo a estrutura existente
3. Mantenha a consistência visual
4. Teste sempre em dispositivos móveis

---

**Nota**: Este clone foi criado especificamente para uso informativo no Shopify, removendo todas as funcionalidades de e-commerce conforme solicitado.
