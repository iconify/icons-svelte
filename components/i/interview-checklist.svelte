<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y_rso8g0p"/><path class="punjz8myo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:interview-checklist" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.punjz8myo) {
  d: path("m5.5 6.5l1 1l1.75-2m2.5 1h7.75M5.5 10l1 1l1.75-2m2.5 1h7.75m-13 3.5l1 1l1.75-2m2.5 1H16");
}

:global(.y_rso8g0p) {
  d: path("M2.5 5A2.5 2.5 0 0 1 5 2.5h14A2.5 2.5 0 0 1 21.5 5v10a2.5 2.5 0 0 1-2.5 2.5h-8L7 21v-3.5H5A2.5 2.5 0 0 1 2.5 15Z");
}

</style>
