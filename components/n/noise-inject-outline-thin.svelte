<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tgth1rbuy"/><path class="lzdsnnb7v"/><path class="ydp7-vbsy"/><path class="rod9nhbdx"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:noise-inject-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lzdsnnb7v) {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.rod9nhbdx) {
  d: path("m10 12.5 2 2 2 -2");
}

:global(.tgth1rbuy) {
  d: path("M6 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

:global(.ydp7-vbsy) {
  d: path("M16 4.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
