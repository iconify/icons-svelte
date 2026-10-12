<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="t2gi8bw3v"/><circle class="k7o8eob8y"/><path class="g5fuvacpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:clown-sharp" {...props}></Icon>
<style>
:global(.c6vt1lbds) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.g5fuvacpp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15.25c1.25 2 3 3 5 3s3.75-1 5-3");
}

:global(.k7o8eob8y) {
  cx: 12px;
  cy: 13px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t2gi8bw3v) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 8.5h.01m6.49 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
