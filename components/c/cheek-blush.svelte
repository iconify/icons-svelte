<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qf4v1x4zs"/><path class="wue2hobiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cheek-blush" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qf4v1x4zs) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M9 9.5h.01m5.99 0h.01");
}

:global(.wue2hobiv) {
  d: path("M13.949 15.625a2.25 2.25 0 0 1-3.898 0M5.5 13.25a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0m10 0a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0");
}

</style>
