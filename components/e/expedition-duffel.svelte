<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bxvqi6gum"/><path class="nx2_xubey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:expedition-duffel" {...props}></Icon>
<style>
:global(.bxvqi6gum) {
  d: path("M10.25 7h3.5A5.25 5.25 0 0 1 19 12.25v4a5.25 5.25 0 0 1-5.25 5.25h-3.5A5.25 5.25 0 0 1 5 16.25v-4A5.25 5.25 0 0 1 10.25 7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nx2_xubey) {
  d: path("M9 21.5v-16a3 3 0 0 1 6 0v16");
}

</style>
