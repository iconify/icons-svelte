<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yh3olpbzx"/><path class="vcly1bc9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:egg-box-six" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vcly1bc9l) {
  d: path("M4.25 10.5a1.75 4.5 0 0 1 3.5 0m2.5 0a1.75 4.5 0 0 1 3.5 0m2.5 0a1.75 4.5 0 0 1 3.5 0M6.5 14.25h11");
}

:global(.yh3olpbzx) {
  d: path("M4.778 10.5h14.444a1.75 1.75 0 0 1 1.691 2.201l-1.067 4A1.75 1.75 0 0 1 18.156 18H5.844a1.75 1.75 0 0 1-1.69-1.299l-1.067-4A1.75 1.75 0 0 1 4.778 10.5");
}

</style>
