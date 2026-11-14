<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gry5v8u2o"/><path class="vnh1r6qxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bee-skep" {...props}></Icon>
<style>
:global(.gry5v8u2o) {
  d: path("M4 20.5C4 12 7 4 12 4s8 8 8 16.5Zm.5-5h15M5.75 10h12.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vnh1r6qxc) {
  d: path("M10 20.5a2 2 0 0 1 4 0");
}

</style>
