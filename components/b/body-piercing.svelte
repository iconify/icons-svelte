<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="el6ejpbjk"/><path class="j6dui_bbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:body-piercing" {...props}></Icon>
<style>
:global(.el6ejpbjk) {
  d: path("M14 5.25a8 8 0 1 1-4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j6dui_bbd) {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
