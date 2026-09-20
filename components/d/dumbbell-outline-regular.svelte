<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vslz5yb3q"/><path class="xhm9ckc2y"/><path class="gl0vd86ea"/><path class="h26bvabki"/><path class="tmc4aacim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dumbbell-outline-regular" {...props}></Icon>
<style>
:global(.gl0vd86ea) {
  d: path("M18 7v10");
}

:global(.h26bvabki) {
  d: path("M3 9v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tmc4aacim) {
  d: path("M21 9v6");
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

:global(.xhm9ckc2y) {
  d: path("M6 7v10");
}

</style>
