<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7qjn6psg"/><path class="hbsd9b23u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:moon-waning" {...props}></Icon>
<style>
:global(.hbsd9b23u) {
  fill: currentColor;
  d: path("M14 3.25a9 9 0 1 0 0 17.5a9 9 0 0 1 0-17.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j7qjn6psg) {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0");
}

</style>
