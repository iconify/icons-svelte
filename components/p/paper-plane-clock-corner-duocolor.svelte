<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ag8_16a4o"/><path class="vp370bb3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paper-plane-clock-corner-duocolor" {...props}></Icon>
<style>
:global(.ag8_16a4o) {
  stroke-opacity: 0.4;
  d: path("m7 8l1-1m4 10a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vp370bb3t) {
  d: path("M9 4L3 6l4 2l2 4l3-9z");
}

</style>
