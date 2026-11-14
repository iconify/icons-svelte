<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xz88pys9y"/><path class="ciw3f0c3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:electric-wheelchair" {...props}></Icon>
<style>
:global(.ciw3f0c3d) {
  d: path("M6 3.5v8h7.5l3 6h4m-2.25 3a.25.25 0 1 0 .5 0a.25.25 0 1 0-.5 0M8.5 14l-1 2.5H9L8 19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xz88pys9y) {
  d: path("M3.5 16.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>
