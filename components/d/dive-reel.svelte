<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uoszapb9r"/><path class="absyqjjes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dive-reel" {...props}></Icon>
<style>
:global(.absyqjjes) {
  d: path("M7.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M10 4.5h7.5a3 3 0 0 1 3 3V20");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uoszapb9r) {
  d: path("M2.5 12a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

</style>
