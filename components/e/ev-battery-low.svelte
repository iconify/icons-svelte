<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tya7042sq"/><path class="ybiyq7bzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ev-battery-low" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tya7042sq) {
  d: path("M4.25 12H2.5V8L5 7l2.5-4h7L18 7l3.5 1v4h-1.75m-11 0h6.5");
}

:global(.ybiyq7bzp) {
  d: path("M4.25 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m11 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M15 17h4.5a1 1 0 0 1 1 1v.5h1V20h-1v.5a1 1 0 0 1-1 1H15a1 1 0 0 1-1-1V18a1 1 0 0 1 1-1m1.25 2.25h.01");
}

</style>
