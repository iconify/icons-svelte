<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uflifulza"/><path class="xp1_wt6oq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:guest-arrival-time" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uflifulza) {
  d: path("M5.5 10.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0M3 21l4.75-4.75");
}

:global(.xp1_wt6oq) {
  d: path("M4.25 16.25h3.5v3.5M13.5 6v4.5l3 2");
}

</style>
