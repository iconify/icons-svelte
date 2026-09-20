<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xd7tu58at"/><path class="qgpt01boe"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:ml-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.qgpt01boe) {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 4l3.2 1.344v13.392L4 20zm4.267 6.4l3.2 1.344v5.392l-3.2 1.264zM20 20l-3.2-1.344V5.264L20 4zm-4.267-6.4l-3.2-1.344V6.864l3.2-1.264z");
}

:global(.xd7tu58at) {
  fill: var(--svg-color--11967f, #11967f);
  d: path("M24 0H0v24h24z");
}

</style>
