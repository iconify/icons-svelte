<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="is08t52yx"/><path class="yzr2dtb9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-to-line-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.is08t52yx) {
  d: path("M3 20L3 4");
}

:global(.yzr2dtb9o) {
  d: path("M21 12L8 12M12.375 16L8 12L12.375 8");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
