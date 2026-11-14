<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ezwe-lb2x"/><path class="bj06q5bss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bus-charging-mast" {...props}></Icon>
<style>
:global(.bj06q5bss) {
  d: path("M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M9 9.5v-3L13 3M2.5 13h19");
}

:global(.ezwe-lb2x) {
  d: path("M2.5 3h19m-19 14v-6A1.5 1.5 0 0 1 4 9.5h15l2.5 2.5v5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
