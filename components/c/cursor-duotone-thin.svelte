<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wqyzvvbsm"/><path class="sm7mmswkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cursor-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sm7mmswkd) {
  d: path("M7 3v15.5l3 -3 3.5 3.5 2.5 -2.5 -3.5 -3.5H17Z");
}

:global(.wqyzvvbsm) {
  fill: currentColor;
  d: path("M7 3v15.5l3 -3 3.5 3.5 2.5 -2.5 -3.5 -3.5H17Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
