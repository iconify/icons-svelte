<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m6se56bni"/><path class="i3hu9d5_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:alpine-meadow" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i3hu9d5_g) {
  d: path("M8.5 20q5.5-8.5 13-6m-7.75 3.25h.01m4.24 0h.01");
}

:global(.m6se56bni) {
  d: path("M2.5 20h19m-19 0L10 4l5 10");
}

</style>
