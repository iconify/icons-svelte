<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="avs7pybtk"/><path class="bwqn15byx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:loafer" {...props}></Icon>
<style>
:global(.avs7pybtk) {
  d: path("M2.5 17.5v-10l5 2l4-3q6.5 1 9 5.25q1 1.75 1 3.5v2.25Zm0-2.25h19");
}

:global(.bwqn15byx) {
  d: path("M10.25 7.5Q13.5 12 17 8.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
