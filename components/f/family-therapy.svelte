<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1n5x74-z"/><path class="miu1uib0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:family-therapy" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.miu1uib0r) {
  d: path("M6.5 11.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M5.25 21.5V20a3.25 3.25 0 0 1 6.5 0v1.5M15 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-.5 6.5v-1a2 2 0 0 1 4 0v1");
}

:global(.o1n5x74-z) {
  d: path("m3.166 9.475l7.75-6.119a1.75 1.75 0 0 1 2.168 0l7.75 6.119a1.75 1.75 0 0 1 .666 1.373v8.902a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75v-8.902a1.75 1.75 0 0 1 .666-1.373");
}

</style>
