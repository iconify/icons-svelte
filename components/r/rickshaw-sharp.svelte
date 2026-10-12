<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xbxre6a9r"/><circle class="ki_c6cb0n"/><path class="lznraacca"/><path class="t9ep2i0ft"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rickshaw-sharp" {...props}></Icon>
<style>
:global(.ki_c6cb0n) {
  cx: 8px;
  cy: 18px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lznraacca) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 18h.01");
}

:global(.t9ep2i0ft) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13 13.5l8.25 5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.xbxre6a9r) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 14.25v-5H7V12h6v3H3.25zm0-8v-3.5H10");
}

</style>
