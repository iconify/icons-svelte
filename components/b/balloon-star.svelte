<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tlywzs5zf"/><path class="if-qhtb4f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:balloon-star" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.if-qhtb4f) {
  d: path("M12 13.5c0 3 1.5 4.5.5 8");
}

:global(.tlywzs5zf) {
  d: path("m13.029 5.084l.621 1.259a1.75 1.75 0 0 0 1.318.958l1.389.202a1.147 1.147 0 0 1 .636 1.956l-1.005.98a1.75 1.75 0 0 0-.504 1.549l.238 1.384a1.147 1.147 0 0 1-1.665 1.21l-1.243-.654a1.75 1.75 0 0 0-1.628 0l-1.243.654a1.147 1.147 0 0 1-1.665-1.21l.238-1.384a1.75 1.75 0 0 0-.504-1.549l-1.005-.98a1.147 1.147 0 0 1 .636-1.956l1.389-.202a1.75 1.75 0 0 0 1.318-.958l.621-1.259a1.147 1.147 0 0 1 2.058 0");
}

</style>
