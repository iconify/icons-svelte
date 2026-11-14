<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hrn_aj3jr"/><path class="a2vyczbel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fencer-lunge" {...props}></Icon>
<style>
:global(.a2vyczbel) {
  d: path("M9.5 6.5L10 13l-7 8.5m7-8.5l6 2v6.5m-6.25-12H15l6.5-3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hrn_aj3jr) {
  d: path("M7.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
