<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpfjf0vyp"/><path class="q4wmzff-d"/><path class="pn42l3bzi"/><path class="cr-sgnwzx"/><path class="pxuv15bph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-indent-decrease-broken" {...props}></Icon>
<style>
:global(.cr-sgnwzx) {
  d: path("M3 18H21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pn42l3bzi) {
  d: path("M11 14H21");
}

:global(.pxuv15bph) {
  d: path("M6.5714 9L4 12L6.5714 15");
}

:global(.q4wmzff-d) {
  d: path("M11 10H21");
}

:global(.zpfjf0vyp) {
  d: path("M3 6H21");
}

</style>
