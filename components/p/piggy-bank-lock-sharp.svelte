<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bqkzv4btb"/><circle class="nr25s3eql"/><path class="i7yv4ebjb"/><path class="xqx6wkbem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:piggy-bank-lock-sharp" {...props}></Icon>
<style>
:global(.bqkzv4btb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 14A7.5 5.75 0 0 1 11 8.25h2a7 5.75 0 0 1 5.75 3h2v5.25h-2.4a7 5.75 0 0 1-2.6 2.25v2H12v-1.5H9.25v1.5H5.5v-2.8a5.75 5.75 0 0 1-2-3.95Z");
}

:global(.i7yv4ebjb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 11.25h3");
}

:global(.nr25s3eql) {
  cx: 11.5px;
  cy: 4.25px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.xqx6wkbem) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 13h.01");
}

</style>
