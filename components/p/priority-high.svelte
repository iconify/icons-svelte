<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ihvl-zl6o"/><path class="yrfw9q2nk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:priority-high" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ihvl-zl6o) {
  d: path("M5.5 10L12 3.5l6.5 6.5");
}

:global(.yrfw9q2nk) {
  d: path("M5.5 15.5L12 9l6.5 6.5m-11 5h9");
}

</style>
