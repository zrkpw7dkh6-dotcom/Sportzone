# SPORTZONE — starter PWA

Aplicação web responsiva em React + TypeScript + Vite, com interface em português, navegação, filtros de partidas, busca, favoritos locais e layout adaptado para celular.

## Rodar localmente

1. Instale Node.js 20 ou superior.
2. No terminal, entre na pasta `sportzone`.
3. Execute `npm install`.
4. Execute `npm run dev`.
5. Abra o endereço local mostrado pelo Vite.

Para gerar a versão de produção: `npm run build`. Os arquivos finais ficam em `dist/`.

## Importante sobre os dados

Esta primeira entrega é um protótipo funcional de interface. Os placares, jogos e manchetes exibidos são dados demonstrativos, não resultados ao vivo. Para dados reais, conecte um provedor esportivo (por exemplo, API-Football) e um provedor/licença de notícias por meio de um backend. Não coloque chaves secretas no navegador.

## Próximas integrações recomendadas

- Backend/API própria para consultar e normalizar jogos, eventos e classificações.
- Supabase para autenticação, banco de dados e preferências sincronizadas.
- WebSocket ou polling controlado para atualizar placares ao vivo.
- Fonte de notícias autorizada, respeitando direitos de reprodução e imagens.
- Push notifications com consentimento do usuário.

## PWA

O projeto inclui `manifest.webmanifest` e um service worker simples para cache do app shell. Para publicar, use hospedagem com HTTPS.
