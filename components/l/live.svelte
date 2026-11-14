<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rf2o4ub-c"/><path class="dyh4jubci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:live" {...props}></Icon>
<style>
:global(.dyh4jubci) {
  d: path("M15.889 8.111a5.5 5.5 0 0 1 0 7.778m-7.778 0a5.5 5.5 0 0 1 0-7.778m11.166-2.217a9.5 9.5 0 0 1 0 12.212m-14.554 0a9.5 9.5 0 0 1 0-12.212");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rf2o4ub-c) {
  fill: currentColor;
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
