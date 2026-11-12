<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w85zccbro"/><path class="pxuv15bph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-indent-decrease-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pxuv15bph) {
  d: path("M6.5714 9L4 12L6.5714 15");
}

:global(.w85zccbro) {
  d: path("M3 6H21M11 10H21M11 14H21M3 18H21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
