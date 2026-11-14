<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kh6cjybjd"/><path class="qp1iy7smw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hydrogen-truck" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kh6cjybjd) {
  d: path("M2.5 14.5h19V10l-3-3.5h-4v8");
}

:global(.qp1iy7smw) {
  d: path("M5.5 5.5h3a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-3a3 3 0 0 1-3-3a3 3 0 0 1 3-3m-.5 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
