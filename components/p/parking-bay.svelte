<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yxj9b3b3t"/><path class="ss1knmssx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:parking-bay" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ss1knmssx) {
  d: path("M9 7h3a3 3 0 0 1 0 6H9");
}

:global(.yxj9b3b3t) {
  d: path("M3.5 3v18h17V3M9 17.5V7");
}

</style>
