<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="qm410xb6n"/><path class="mh32_mbuf"/><path class="jm65bxmpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:modem-sharp" {...props}></Icon>
<style>
:global(.jm65bxmpq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 13h1.5");
}

:global(.mh32_mbuf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 13h.01m2.99 0h.01m2.99 0h.01");
}

:global(.qm410xb6n) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75h18.5v8.5H2.75zm3.5 8.5v2.5m11.5-2.5v2.5m-2-11v-6h5.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
