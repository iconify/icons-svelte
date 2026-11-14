<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="polw-1gzh"/><path class="vhgoflfvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pet-lost-cover" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.polw-1gzh) {
  d: path("M3.5 10.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0m12 5l5 5");
}

:global(.vhgoflfvx) {
  d: path("M10.5 14.5c-1.25 0-2-.6-2-1.5c0-.75 1-1.25 2-1.25s2 .5 2 1.25c0 .9-.75 1.5-2 1.5M8 10.25h.01M9.5 8.5h.01m1.99 0h.01M13 10.25h.01");
}

</style>
