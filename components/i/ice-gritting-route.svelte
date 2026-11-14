<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s5qxv-f-x"/><path class="k56yy8bds"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ice-gritting-route" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k56yy8bds) {
  d: path("M8.5 17a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M4.5 9h.01M3 12.5h.01M4.5 16h.01");
}

:global(.s5qxv-f-x) {
  d: path("M7.5 15V6.5A1.5 1.5 0 0 1 9 5h6.5v3h3l3 3.5V15Z");
}

</style>
