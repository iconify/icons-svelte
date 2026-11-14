<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vbh3wac6q"/><path class="kuc0_9bqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:energy-saving" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kuc0_9bqn) {
  d: path("M10 12.5c0-3.5 1.5-5 4.5-5.5c0 3-1.5 5-4.5 5.5");
}

:global(.vbh3wac6q) {
  d: path("M9 18v-3.25a6.5 6.5 0 1 1 6 0V18Zm.5 3h5");
}

</style>
