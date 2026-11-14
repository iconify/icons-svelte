<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="ewwenw0ef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:aperture-narrow" {...props}></Icon>
<style>
:global(.ewwenw0ef) {
  d: path("m13.575 12.744l-.143.25a1.5 1.5 0 0 1-1.302.756h-.26a1.5 1.5 0 0 1-1.302-.756l-.143-.25a1.5 1.5 0 0 1 0-1.488l.143-.25a1.5 1.5 0 0 1 1.302-.756h.26a1.5 1.5 0 0 1 1.302.756l.143.25a1.5 1.5 0 0 1 0 1.488M14 12l4.25 7.25M13 13.75L8.75 21M11 13.75H2.75M10 12L5.75 4.75m5.25 5.5L15.25 3M13 10.25h8.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
