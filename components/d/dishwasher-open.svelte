<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zj4g8hi0t"/><path class="rc3512byc"/><path class="qjp3ou2ni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dishwasher-open" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qjp3ou2ni) {
  d: path("M8 16a4 4 0 0 1 8 0");
}

:global(.rc3512byc) {
  d: path("M5.337 16h13.326a1.75 1.75 0 0 1 1.689 1.29l.545 2a1.75 1.75 0 0 1-1.688 2.21H4.791a1.75 1.75 0 0 1-1.688-2.21l.545-2A1.75 1.75 0 0 1 5.337 16M4 6h16");
}

:global(.zj4g8hi0t) {
  d: path("M7.5 2.5h9A3.5 3.5 0 0 1 20 6v6.5a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 12.5V6a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
