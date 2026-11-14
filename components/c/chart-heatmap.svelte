<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m7ekf0b1t"/><path class="e9_wheb8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-heatmap" {...props}></Icon>
<style>
:global(.e9_wheb8f) {
  fill: currentColor;
  d: path("M17 2.5h4.5V7H17ZM9.75 9.75h4.5v4.5h-4.5Zm0 7.25h4.5v4.5h-4.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m7ekf0b1t) {
  d: path("M2.5 2.5H7V7H2.5Zm7.25 0h4.5V7h-4.5ZM2.5 9.75H7v4.5H2.5Zm14.5 0h4.5v4.5H17ZM2.5 17H7v4.5H2.5ZM17 17h4.5v4.5H17Z");
}

</style>
