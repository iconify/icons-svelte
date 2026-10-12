<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z34r1obsd"/><path class="m9f7spw1x"/><circle class="a9bxk79um"/><circle class="jn0v4eh1r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:free-shipping-sharp" {...props}></Icon>
<style>
:global(.a9bxk79um) {
  cx: 7px;
  cy: 19px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jn0v4eh1r) {
  cx: 17.5px;
  cy: 19px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m9f7spw1x) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 10.75h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.z34r1obsd) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.5h8.75V14H2.75zm12.75 1h4l1.75 2.5v4H14.5V7.5z");
}

</style>
