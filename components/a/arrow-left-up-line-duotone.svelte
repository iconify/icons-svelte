<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l6ar3parr"/><path class="bq84y5bti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-up-line-duotone" {...props}></Icon>
<style>
:global(.bq84y5bti) {
  d: path("M15 6H6V15");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l6ar3parr) {
  d: path("M18 18L6 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
