<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tkrcfhgkm"/><path class="m33ss0bea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:debug-restart" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m33ss0bea) {
  d: path("M18 2.5V6h-3.5");
}

:global(.tkrcfhgkm) {
  d: path("M20.5 12A8.5 8.5 0 1 1 18 6");
}

</style>
