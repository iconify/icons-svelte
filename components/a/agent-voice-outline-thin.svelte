<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dxqp15kpa"/><path class="g_ig5r7qc"/><path class="os75hg6rr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-voice-outline-thin" {...props}></Icon>
<style>
:global(.dxqp15kpa) {
  d: path("M8.69 8.37a4 4 0 1 1 -3.38 0");
}

:global(.g_ig5r7qc) {
  d: path("M17.12 9.88a3 3 0 0 1 0 4.24");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.os75hg6rr) {
  d: path("M19.24 7.76a6 6 0 0 1 0 8.5");
}

</style>
