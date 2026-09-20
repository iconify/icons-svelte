<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x_i-jbbeq"/><path class="oayjtvtuh"/><path class="yxwimoiqt"/><path class="klj1k5byh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:haptic-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.klj1k5byh) {
  d: path("M4.17 14.83a4 4 0 0 1 0 -5.66");
}

:global(.oayjtvtuh) {
  d: path("M8 5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.x_i-jbbeq) {
  fill: currentColor;
  d: path("M8 5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yxwimoiqt) {
  d: path("M19.83 9.17a4 4 0 0 1 0 5.66");
}

</style>
