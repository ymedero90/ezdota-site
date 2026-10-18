# EZ Dota — Privacy Policy / Política de privacidad

_Last updated: 18 October 2026 · Última actualización: 18 de octubre de 2026_

## English

EZ Dota ("the app") is an independent companion app for Dota 2 made by Yoel Medero Vargas. It is not affiliated with or endorsed by Valve Corporation. Dota 2 is a trademark of Valve Corporation.

### What the app stores
- **On your device only**: the Dota account you linked, your friends list, favorite heroes and teams, your builds, Twitch favorites, the daily medal snapshot, alert preferences, app settings and, if you enter one, your Anthropic API key for the AI coach. Deleting the app deletes all of it.
- **In your EZ Dota account (optional)**: if you sign in with Apple, Google or an email code, the app stores on our servers (Supabase): your account id, email and name (if the sign-in provider shares it), your linked Dota account id and, if you verify it, your Steam account id, your friends list, your builds (private ones visible only to you), your Arena duels and tournaments, your "find a team" post while it is live, friend requests, the users you block and the reports you send. This is what lets you use the same data on several devices and share things with friends.
- **Nothing else**: no contacts, no location, no advertising identifiers, no analytics or tracking profiles.

### EZ Dota Pro (subscription)
EZ Dota Pro is an optional auto-renewing subscription sold through the App Store or Google Play. Payment is handled entirely by Apple or Google; we never see your card or payment details. To know who is subscribed, the app uses **RevenueCat** (revenuecat.com), which receives the store's purchase records (product, dates, renewal status, country and price) together with an app user id: your EZ Dota account id if you are signed in, or a random id if you are not. We use this only to unlock Pro on your devices. You manage or cancel the subscription in your App Store or Google Play account settings; deleting your EZ Dota account does not cancel it.

### Where the data comes from
Match statistics, player profiles, rankings and pro games come from the public **OpenDota** API (opendota.com), which reads data Valve exposes for players who enabled "Expose Public Match Data" in Dota 2. Hero, item and ability data come from **dota2.com**. Live games in the Live Tracker come from Valve's **Steam Web API**, fetched by our server. Live streams, clips and channels come from the **Twitch** API through our server; the app never asks for your Twitch password. Highlights open **YouTube**, and Steam profile links open **steamcommunity.com**.

### Sign-in and Steam verification
Sign in with Apple, Google or an email code is handled by Supabase and the provider you choose; we receive your email and, if shared, your name. "Verify with Steam" sends you to Steam's own login page; we only receive your public Steam id to confirm the Dota account is yours. We never see your Steam password.

### AI coach
The AI match analysis is optional and uses an **Anthropic** API key that you enter yourself. When you ask for an analysis, the app sends a summary of that match (heroes, items, stats, timings) directly from your device to Anthropic (anthropic.com) with your key, under Anthropic's terms; we don't receive it.

### Notifications and background checks
If you enable alerts, the app periodically asks OpenDota for your (and your friends') latest match and for live pro games in the background and shows local notifications. Nothing about this leaves your device except those requests.

### Your rights
You can delete your EZ Dota account at any time from Settings → your account → "Delete my account"; this removes everything stored on our servers. To have your RevenueCat purchase records deleted, write to us. For any question write to **ezdota.app@gmail.com**.

### Children
The app is not directed at children under 13.

---

## Español

EZ Dota ("la app") es una app complementaria independiente para Dota 2 hecha por Yoel Medero Vargas. No está afiliada ni respaldada por Valve Corporation. Dota 2 es una marca de Valve Corporation.

### Qué guarda la app
- **Solo en tu dispositivo**: la cuenta de Dota que vinculaste, tu lista de amigos, héroes y equipos favoritos, tus builds, favoritos de Twitch, el historial diario de tu medalla, las preferencias de avisos, los ajustes y, si la pones, tu clave de la API de Anthropic para el coach con IA. Si borras la app, se borra todo.
- **En tu cuenta de EZ Dota (opcional)**: si entras con Apple, Google o un código por email, guardamos en nuestros servidores (Supabase): tu id de cuenta, tu email y tu nombre (si el proveedor lo comparte), tu id de Dota vinculado y, si la verificas, tu id de Steam, tu lista de amigos, tus builds (las privadas solo las ves tú), tus duelos y torneos de Arena, tu anuncio de "buscar equipo" mientras esté activo, las solicitudes de amistad, los usuarios que bloqueas y las denuncias que envías. Es lo que permite usar los mismos datos en varios dispositivos y compartir cosas con amigos.
- **Nada más**: ni contactos, ni ubicación, ni identificadores publicitarios, ni perfiles de analítica o rastreo.

### EZ Dota Pro (suscripción)
EZ Dota Pro es una suscripción opcional de renovación automática que se vende a través de la App Store o Google Play. El pago lo gestionan por completo Apple o Google; nunca vemos tu tarjeta ni tus datos de pago. Para saber quién está suscrito, la app usa **RevenueCat** (revenuecat.com), que recibe los registros de compra de la tienda (producto, fechas, estado de renovación, país y precio) junto con un id de usuario: tu id de cuenta de EZ Dota si has iniciado sesión, o un id aleatorio si no. Solo lo usamos para activar Pro en tus dispositivos. La suscripción se gestiona o cancela en los ajustes de tu cuenta de la App Store o Google Play; borrar tu cuenta de EZ Dota no la cancela.

### De dónde salen los datos
Las estadísticas de partidas, perfiles, rankings y partidas pro vienen de la API pública de **OpenDota** (opendota.com), que lee los datos que Valve expone de los jugadores con "Exponer datos públicos de partidas" activado en Dota 2. Héroes, objetos y habilidades vienen de **dota2.com**. Las partidas en vivo del Live Tracker vienen de la **Steam Web API** de Valve, consultada por nuestro servidor. Streams, clips y canales vienen de la API de **Twitch** a través de nuestro servidor; la app nunca pide tu contraseña de Twitch. Los highlights abren **YouTube** y los enlaces a perfiles de Steam abren **steamcommunity.com**.

### Inicio de sesión y verificación con Steam
El inicio de sesión con Apple, Google o un código por email lo gestionan Supabase y el proveedor que elijas; recibimos tu email y, si lo comparte, tu nombre. "Verificar con Steam" te lleva a la página de inicio de sesión de Steam; solo recibimos tu id público de Steam para confirmar que la cuenta de Dota es tuya. Nunca vemos tu contraseña de Steam.

### Coach con IA
El análisis de partidas con IA es opcional y usa una clave de la API de **Anthropic** que pones tú. Cuando pides un análisis, la app envía un resumen de esa partida (héroes, objetos, estadísticas, tiempos) directamente desde tu dispositivo a Anthropic (anthropic.com) con tu clave, bajo las condiciones de Anthropic; nosotros no lo recibimos.

### Avisos y comprobaciones en segundo plano
Si activas los avisos, la app consulta periódicamente a OpenDota tu última partida (y la de tus amigos) y las partidas pro en vivo, y muestra notificaciones locales. Nada sale de tu dispositivo salvo esas consultas.

### Tus derechos
Puedes borrar tu cuenta de EZ Dota cuando quieras desde Ajustes → tu cuenta → "Borrar mi cuenta"; esto elimina todo lo guardado en nuestros servidores. Para borrar tus registros de compra en RevenueCat, escríbenos. Para cualquier duda escribe a **ezdota.app@gmail.com**.

### Menores
La app no está dirigida a menores de 13 años.
