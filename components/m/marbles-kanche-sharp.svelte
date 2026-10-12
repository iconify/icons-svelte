<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="n5jjp8icf"/><circle class="ol_gbdb3r"/><circle class="kkrhs2bdf"/><path class="fqqvecces"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:marbles-kanche-sharp" {...props}></Icon>
<style>
:global(.fqqvecces) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.1 6.8h.01");
}

:global(.kkrhs2bdf) {
  cx: 12px;
  cy: 7.84px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n5jjp8icf) {
  cx: 7px;
  cy: 16.5px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ol_gbdb3r) {
  cx: 17px;
  cy: 16.5px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
