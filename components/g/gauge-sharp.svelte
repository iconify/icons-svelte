<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yd4kwwgnv"/><circle class="ejmel3lck"/><path class="qlp8a7bwg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gauge-sharp" {...props}></Icon>
<style>
:global(.ejmel3lck) {
  cx: 12px;
  cy: 13.25px;
  r: 2px;
}

:global(.qlp8a7bwg) {
  d: path("m13.28 11.71l2.47-2.96");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yd4kwwgnv) {
  d: path("M5.46 19.79a9.25 9.25 0 1 1 13.08 0");
}

</style>
