<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c0jfp4b4d"/><path class="v2jzgr56j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gps-track" {...props}></Icon>
<style>
:global(.c0jfp4b4d) {
  d: path("M16.5 15s-4-4.25-4-7.5a4 4 0 0 1 8 0c0 3.25-4 7.5-4 7.5m-13 2h.01m2.99 3.5h.01m3.99-1h.01M13.5 17h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v2jzgr56j) {
  d: path("M15 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
