<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrjqjgbgu"/><path class="g_godccaa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:burnup-chart" {...props}></Icon>
<style>
:global(.g_godccaa) {
  d: path("m7 17l4.5-4l3.5-2l4-4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zrjqjgbgu) {
  d: path("M3.5 3.5v17h17M7 6.5h13.5");
}

</style>
