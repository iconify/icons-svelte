<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="w0yu57t3m"/><path class="z3mxmfbuu"/><circle class="rdo2hgb7w"/><path class="to8m3ibcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:brake-disc-sharp" {...props}></Icon>
<style>
:global(.c6vt1lbds) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rdo2hgb7w) {
  cx: 12px;
  cy: 12px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.to8m3ibcr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.w0yu57t3m) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.28 15.63h.01M12 19.25h.01m-6.29-3.62h.01m-.01-7.25h.01M12 4.75h.01m6.27 3.63h.01");
}

:global(.z3mxmfbuu) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 12a5.25 5.25 0 1 0-10.5 0a5.25 5.25 0 0 0 10.5 0Z");
}

</style>
