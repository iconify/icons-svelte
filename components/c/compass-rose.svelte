<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tk6eyp-3h"/><path class="jl72gcylo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:compass-rose" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jl72gcylo) {
  d: path("M5.25 12a6.75 6.75 0 1 0 13.5 0a6.75 6.75 0 1 0-13.5 0");
}

:global(.tk6eyp-3h) {
  d: path("m12.875 6.375l.666 2.951a1.5 1.5 0 0 0 1.133 1.133l2.951.666a.897.897 0 0 1 0 1.75l-2.951.666a1.5 1.5 0 0 0-1.133 1.133l-.666 2.951a.897.897 0 0 1-1.75 0l-.666-2.951a1.5 1.5 0 0 0-1.133-1.133l-2.951-.666a.897.897 0 0 1 0-1.75l2.951-.666a1.5 1.5 0 0 0 1.133-1.133l.666-2.951a.897.897 0 0 1 1.75 0");
}

</style>
