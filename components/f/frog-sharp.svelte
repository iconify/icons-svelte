<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="docctur_i"/><path class="y6uprylka"/><path class="qzb6f1vsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:frog-sharp" {...props}></Icon>
<style>
:global(.docctur_i) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.92 10.05a3 3 0 1 1 4.52-3.13a7.25 7.25 0 0 1 3.12 0a3 3 0 1 1 4.52 3.13a7.25 7.25 0 1 1-12.16 0Z");
}

:global(.qzb6f1vsy) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 15.25c2.25 1.75 5.75 1.75 8 0");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.y6uprylka) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 7.5h.01m8.99 0h.01");
}

</style>
