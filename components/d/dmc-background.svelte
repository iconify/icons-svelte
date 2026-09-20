<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hu2c5ux3x"/><path class="chenckbmr"/><path class="cmukp8dbo"/><path class="w4hgxzbuz"/><path class="z5su1j9ts"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:dmc-background" {...props}></Icon>
<style>
:global(.chenckbmr) {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.96 10.75l-1.245-5.5l3.315 5.5zm0 0l-2.96 8l5.03-8z");
}

:global(.cmukp8dbo) {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.7 5.264L4 18.75l3-8zm11.34 5.486l1.245-5.5l-3.315 5.5zm0 0l2.96 8l-5.03-8z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.hu2c5ux3x) {
  fill: var(--svg-color--001e1e, #001e1e);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.w4hgxzbuz) {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.3 5.264L20 18.75l-3-8zM12 9.65s-1.9.68-2.855 1.01L12 15.265zm0-.005s1.91.685 2.86 1.015l-2.854 4.605V9.65z");
}

:global(.z5su1j9ts) {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 9.665l-2.855 1.01L12 6.075zm0 0l2.86 1L12 6.075z");
}

</style>
