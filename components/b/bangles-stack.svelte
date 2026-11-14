<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7bskx1es"/><path class="qazr6nb-c"/><path class="k7nrqubgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bangles-stack" {...props}></Icon>
<style>
:global(.e7bskx1es) {
  d: path("M2.5 7a7.5 3.5 0 1 0 15 0a7.5 3.5 0 1 0-15 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k7nrqubgq) {
  d: path("M6.5 17a7.5 3.5 0 1 0 15 0a7.5 3.5 0 1 0-15 0");
}

:global(.qazr6nb-c) {
  d: path("M4.5 12a7.5 3.5 0 1 0 15 0a7.5 3.5 0 1 0-15 0");
}

</style>
