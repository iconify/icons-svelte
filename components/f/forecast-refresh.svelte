<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yb4l-1b5j"/><path class="g-bs5e8bx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:forecast-refresh" {...props}></Icon>
<style>
:global(.g-bs5e8bx) {
  d: path("M15.25 2.5L16 5l-2.5.75m-4 8.75h5a2 2 0 0 0 0-4a3 3 0 0 0-5.5.75a1.65 1.65 0 0 0 .5 3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yb4l-1b5j) {
  d: path("M12 4a8 8 0 1 1-6.928 4");
}

</style>
