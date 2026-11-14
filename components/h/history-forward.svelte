<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sal6b-b0f"/><path class="ix8gp5a6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:history-forward" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ix8gp5a6t) {
  d: path("m16 9l3 3l3-3M11 7.5V12l-3 2");
}

:global(.sal6b-b0f) {
  d: path("M15 18.928A8 8 0 1 1 19 12");
}

</style>
