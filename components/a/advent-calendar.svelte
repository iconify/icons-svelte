<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ndyognaas"/><path class="ytx4uxopf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:advent-calendar" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ndyognaas) {
  d: path("M6.5 4.5h11A3.5 3.5 0 0 1 21 8v9.5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5V8a3.5 3.5 0 0 1 3.5-3.5m1.5-2v4m8-4v4m-13 3h18M3 15h18M9 9.5V21m6-11.5V21");
}

:global(.ytx4uxopf) {
  d: path("m9 9.5l2.75 1.5v3M18 18h.01");
}

</style>
