<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1n5x74-z"/><path class="n-vqf9leg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:occupancy-sensor" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n-vqf9leg) {
  d: path("M9.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M7 21.5c0-3 2.25-4.5 5-4.5s5 1.5 5 4.5");
}

:global(.o1n5x74-z) {
  d: path("m3.166 9.475l7.75-6.119a1.75 1.75 0 0 1 2.168 0l7.75 6.119a1.75 1.75 0 0 1 .666 1.373v8.902a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75v-8.902a1.75 1.75 0 0 1 .666-1.373");
}

</style>
