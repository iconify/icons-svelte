<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><circle class="fw2awacyd"/><path class="gjm7u7v1y"/><path class="qyrds1bwu"/><path class="ea5fdbqox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:instant-camera-sharp" {...props}></Icon>
<style>
:global(.ea5fdbqox) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 17.75h10.5");
}

:global(.fw2awacyd) {
  cx: 12px;
  cy: 11.25px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.gjm7u7v1y) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 6.25h2.5");
}

:global(.qyrds1bwu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 6.25h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.ywno-sh7h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
