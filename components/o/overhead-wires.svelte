<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gb_t61b5t"/><path class="nzite7bsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:overhead-wires" {...props}></Icon>
<style>
:global(.gb_t61b5t) {
  d: path("M4 3v18.5M20 3v18.5M4 6q8 5 16 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nzite7bsv) {
  d: path("M4 10q8 5 16 0");
}

</style>
