<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="enn2zbb9x"/><path class="hxkfawbzb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:geyser" {...props}></Icon>
<style>
:global(.enn2zbb9x) {
  d: path("M3 20.5c3.5-3.75 14.5-3.75 18 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hxkfawbzb) {
  d: path("M10.5 17.75V10L7 4m6.5 13.75V10L17 4m-5 1h.01M5 10h.01M19 10h.01");
}

</style>
