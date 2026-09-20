<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a-v3knb-a"/><path class="bjo0kbbwk"/><path class="x4l5r-bat"/><path class="hrm50umfz"/><path class="lwlflab4b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:heap-outline-regular" {...props}></Icon>
<style>
:global(.a-v3knb-a) {
  d: path("M3 14a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.bjo0kbbwk) {
  d: path("M6 16.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hrm50umfz) {
  d: path("M6 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.lwlflab4b) {
  d: path("M14 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x4l5r-bat) {
  d: path("M14 16.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
