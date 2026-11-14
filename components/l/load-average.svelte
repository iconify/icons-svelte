<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dgrcacccd"/><path class="gb0y6-0_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:load-average" {...props}></Icon>
<style>
:global(.dgrcacccd) {
  d: path("M2.5 16a9.5 9.5 0 0 1 19 0");
}

:global(.gb0y6-0_i) {
  d: path("M10.25 16a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M13 14.75l2.75-3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
