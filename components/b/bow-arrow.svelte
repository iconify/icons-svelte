<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eh3gfms5p"/><path class="e5ragzjjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bow-arrow" {...props}></Icon>
<style>
:global(.e5ragzjjw) {
  d: path("M7 9.25L9.5 12L7 14.75");
}

:global(.eh3gfms5p) {
  d: path("M7 2.5c8 3 8 16 0 19m0-19L3 12l4 9.5M3 12h18.5M18 8.5l3.5 3.5l-3.5 3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
