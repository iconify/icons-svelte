<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h_y79_b8s"/><path class="kap574ulx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:mtd-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.h_y79_b8s) {
  fill: var(--svg-color--ff1826, #ff1826);
  d: path("M24 0H0v24h24z");
}

:global(.kap574ulx) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 16h12V4h4v16H4zM4 4h4v6.286H4zm5.714 0h4v6.286h-4z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
