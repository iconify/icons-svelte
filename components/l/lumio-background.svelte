<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGL9bhkWOT)" class="sn85jcbmw"/><path fill="url(#SVG2vwvZcYv)" class="umzjdybgx"/><path class="pb5w4l59c"/></g><defs><linearGradient id="SVGL9bhkWOT" x1="5.745" x2="18.255" y1="12.147" y2="12.246" gradientUnits="userSpaceOnUse"><stop class="zi1c5acua"/><stop offset="1" class="vbd5qwbyz"/></linearGradient><linearGradient id="SVG2vwvZcYv" x1="4" x2="18.255" y1="12.147" y2="12.147" gradientUnits="userSpaceOnUse"><stop class="sw_pnb_jw"/><stop offset="1" class="fqpgn-bey"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:lumio-background" {...props}></Icon>
<style>
:global(.fqpgn-bey) {
  stop-color: var(--svg-color--f03f79, #f03f79);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.mumfproca) {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

:global(.pb5w4l59c) {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.11 13.91A1.9 1.9 0 0 0 20 12a1.9 1.9 0 0 0-1.89-1.91A1.9 1.9 0 0 0 16.217 12a1.9 1.9 0 0 0 1.891 1.91");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.sn85jcbmw) {
  d: path("m4 4.8l14.109 5.29v3.82L4 19.2z");
}

:global(.sw_pnb_jw) {
  stop-color: var(--svg-color--f03f79, #f03f79);
  stop-opacity: 0;
}

:global(.umzjdybgx) {
  d: path("m4 7.739l14.109 2.35v3.821L4 16.261z");
}

:global(.vbd5qwbyz) {
  stop-color: var(--svg-color--8d29c1, #8d29c1);
}

:global(.zi1c5acua) {
  stop-color: var(--svg-color--8d29c1, #8d29c1);
  stop-opacity: 0;
}

</style>
