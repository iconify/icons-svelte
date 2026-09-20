<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGKW34rdfF)" class="t_ix2vbsn"/><path fill="url(#SVG3jIPubUQ)" class="jvi5bvb7k"/><path class="xzcho3bgr"/></g><defs><linearGradient id="SVGKW34rdfF" x1="13.474" x2="12.326" y1="17.109" y2="6.858" gradientUnits="userSpaceOnUse"><stop offset=".1" class="up1ci3wji"/><stop offset=".5" class="tozbrd8sb"/><stop offset=".8" class="qevv1ubck"/></linearGradient><linearGradient id="SVG3jIPubUQ" x1="13.76" x2="12.238" y1="5.338" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".1" class="up1ci3wji"/><stop offset=".5" class="tozbrd8sb"/><stop offset=".8" class="qevv1ubck"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:coti-background" {...props}></Icon>
<style>
:global(.beaf9ac8r) {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jvi5bvb7k) {
  d: path("M19.63 13.345c.255 0 .37-.115.37-.345V7.115c0-.26-.115-.345-.37-.345c-2.85-.025-6.275 2.485-9.13 4.46V18c2.825-1.945 6.36-4.715 9.13-4.655");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.qevv1ubck) {
  stop-color: var(--svg-color--2bbfdf, #2bbfdf);
}

:global(.t_ix2vbsn) {
  d: path("M4.37 10.685c-.255 0-.37.115-.37.345v5.885c0 .255.115.34.37.34c2.825.03 6.275-2.485 9.13-4.455V6c-2.825 1.945-6.36 4.715-9.13 4.685");
}

:global(.tozbrd8sb) {
  stop-color: var(--svg-color--248fcb, #248fcb);
}

:global(.up1ci3wji) {
  stop-color: var(--svg-color--194aad, #194aad);
}

:global(.xzcho3bgr) {
  fill: var(--svg-color--194aad, #194aad);
  d: path("M13.5 12.74V9.183q-1.518 1-3 2.05v3.6c1.05-.685 2.05-1.415 3-2.1z");
}

</style>
