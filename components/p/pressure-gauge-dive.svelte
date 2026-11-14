<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ses8_mp_x"/><path class="et9l4bb9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pressure-gauge-dive" {...props}></Icon>
<style>
:global(.et9l4bb9u) {
  d: path("M11 17.5V19c0 1.75 2 2.5 5 2.5h5M7.818 13.182a4.5 4.5 0 0 1 0-6.364");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ses8_mp_x) {
  d: path("M3.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0m7.5 0l3.5-3.5");
}

</style>
