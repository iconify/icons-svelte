<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w4fe0jbzn"/><path class="stn2q4b5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rotate-3d" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.stn2q4b5m) {
  d: path("M14.25 15.25L17 16.5l-1.25 2.75M12 2.5v19");
}

:global(.w4fe0jbzn) {
  d: path("M21.5 12a9.5 5.25 0 1 0-4.5 4.5");
}

</style>
