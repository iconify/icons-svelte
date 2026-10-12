<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="mtmv_3buk"/><path class="v8khciw_t"/><path class="e9im5mbtf"/><path class="mofoi37tv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coconut-sharp" {...props}></Icon>
<style>
:global(.e9im5mbtf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 16h10.5a5.25 5.25 0 0 1-10.5 0Z");
}

:global(.mofoi37tv) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.6 17.4a2.75 2.75 0 0 0 4.8 0");
}

:global(.mtmv_3buk) {
  cx: 8px;
  cy: 8px;
  r: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.v8khciw_t) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 6.5h.01m2.99 0h.01M8 9h.01");
}

</style>
