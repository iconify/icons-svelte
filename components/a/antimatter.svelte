<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5a6x7pyb"/><path class="hjpo_obda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:antimatter" {...props}></Icon>
<style>
:global(.b5a6x7pyb) {
  fill: currentColor;
  d: path("M2.5 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

:global(.hjpo_obda) {
  d: path("M13.5 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
