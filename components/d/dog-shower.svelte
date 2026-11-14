<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y0wwf9gug"/><path class="y6voxgbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dog-shower" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y0wwf9gug) {
  d: path("M3.5 11a6.5 6.5 0 0 1 13 0Z");
}

:global(.y6voxgbpt) {
  d: path("M10 4.5v-2h10M6 14l-1 3.5m5-3.5v3.5m4-3.5l-.5 2.5m3.75-1h3.5l1 3l-1 .25V20a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5v-1.25l-1-.25Z");
}

</style>
