<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="z66n8cyey"/><path class="ar_wnnypk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:bus-duotone" {...props}></Icon>
<style>
:global(.ar_wnnypk) {
  d: path("M184 32H72a32 32 0 0 0-32 32v144a16 16 0 0 0 16 16h24a16 16 0 0 0 16-16v-16h64v16a16 16 0 0 0 16 16h24a16 16 0 0 0 16-16V64a32 32 0 0 0-32-32M56 176v-56h144v56Zm0-96h144v24H56Zm16-32h112a16 16 0 0 1 16 16H56a16 16 0 0 1 16-16m8 160H56v-16h24Zm96 0v-16h24v16Zm-72-60a12 12 0 1 1-12-12a12 12 0 0 1 12 12m72 0a12 12 0 1 1-12-12a12 12 0 0 1 12 12m72-68v24a8 8 0 0 1-16 0V80a8 8 0 0 1 16 0M24 80v24a8 8 0 0 1-16 0V80a8 8 0 0 1 16 0");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.z66n8cyey) {
  d: path("M48 184h40v24a8 8 0 0 1-8 8H56a8 8 0 0 1-8-8Zm120 24a8 8 0 0 0 8 8h24a8 8 0 0 0 8-8v-24h-40ZM48 72v40h160V72Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
