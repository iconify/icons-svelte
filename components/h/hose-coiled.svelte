<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q8irwoedh"/><path class="i2hlkibed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hose-coiled" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i2hlkibed) {
  d: path("M20 2.5zA1.5 1.5 0 0 1 21.5 4A1.5 1.5 0 0 1 20 5.5A1.5 1.5 0 0 1 18.5 4A1.5 1.5 0 0 1 20 2.5");
}

:global(.q8irwoedh) {
  d: path("M18.5 4H10a8.5 8.5 0 0 1 0 17a7 7 0 0 1 0-14a5.5 5.5 0 0 1 0 11a4 4 0 0 1 0-8");
}

</style>
