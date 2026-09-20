<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yw0xzbbmi"/><path class="n3p0zmbop"/><path class="knng32dgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:more-horizontal-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.knng32dgc) {
  d: path("M18 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.yw0xzbbmi) {
  d: path("M4 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
