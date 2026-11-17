<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w97x3loiu"/><path class="a-3sl3ulc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plane-side-duotone" {...props}></Icon>
<style>
:global(.a-3sl3ulc) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 10h11a2 2 0 1 1 0 4h-4l-5 5H8l2-5H5L3 5h2z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.w97x3loiu) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 10h11a2 2 0 1 1 0 4h-4l-5 5H8l2-5H5L3 5h2Z");
}

</style>
