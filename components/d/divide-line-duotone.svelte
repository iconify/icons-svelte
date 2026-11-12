<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a1d08c85x"/><path class="byh8rvbcw"/><path class="uci4f6n5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:divide-line-duotone" {...props}></Icon>
<style>
:global(.a1d08c85x) {
  d: path("M4 12H20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.byh8rvbcw) {
  d: path("M12 6H12.0001");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uci4f6n5q) {
  d: path("M12 18H12.0001");
}

</style>
