<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="spmb-6bdc"/><circle class="pauvkn1qr"/><path class="qvoc8gbpg"/><circle class="jhfl8tb7m"/><path class="t063bibnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:monster-truck-sharp" {...props}></Icon>
<style>
:global(.jhfl8tb7m) {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pauvkn1qr) {
  cx: 6.5px;
  cy: 17.5px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qvoc8gbpg) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 17.5h.01");
}

:global(.spmb-6bdc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 9V8H11V3.75h4.15l.867-.001l.433.751l1.9 3.5h2.4v3.25H3.25v-1Zm10.5-5.25V8");
}

:global(.t063bibnx) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 17.5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
