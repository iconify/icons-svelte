<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-4-9m5pi"/><path class="jug4q_r3a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-parallel-coordinates" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jug4q_r3a) {
  d: path("m3.5 17.5l8.5-9l8.5 7");
}

:global(.w-4-9m5pi) {
  d: path("M3.5 3v18M12 3v18m8.5-18v18M3.5 6.5l8.5 10L20.5 8");
}

</style>
