<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pqrrdkbgl"/><path class="hqymo8wxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arena-indoor" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hqymo8wxy) {
  d: path("M10 20.5V16a2 2 0 0 1 4 0v4.5");
}

:global(.pqrrdkbgl) {
  d: path("M2.5 20.5V11a9.5 6.5 0 0 1 19 0v9.5Zm0-9.5h19");
}

</style>
