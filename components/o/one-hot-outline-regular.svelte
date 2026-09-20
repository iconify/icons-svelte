<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l2x-_sd5q"/><path class="ct8-554vp"/><path class="olmwgycdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:one-hot-outline-regular" {...props}></Icon>
<style>
:global(.ct8-554vp) {
  d: path("M11 6v12");
}

:global(.l2x-_sd5q) {
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.olmwgycdy) {
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
