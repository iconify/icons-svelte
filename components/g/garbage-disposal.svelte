<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n5wh3h36c"/><path class="jdw2sfbjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:garbage-disposal" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jdw2sfbjf) {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0m3.5-1.5l3 3m0-3l-3 3");
}

:global(.n5wh3h36c) {
  d: path("M11 3.5h2a8.5 8.5 0 0 1 8.5 8.5a8.5 8.5 0 0 1-8.5 8.5h-2A8.5 8.5 0 0 1 2.5 12A8.5 8.5 0 0 1 11 3.5");
}

</style>
