<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ce0dzhbee"/><path class="uf70owbhn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fossil-leaf" {...props}></Icon>
<style>
:global(.ce0dzhbee) {
  d: path("M3.5 8L8 4h10.5L21 9v8l-4 3.5H6L3 16Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uf70owbhn) {
  d: path("M7.5 16.5c0-6.5 3-9 9.5-9c0 6.5-3 9-9.5 9m0 0l6.75-6.5");
}

</style>
