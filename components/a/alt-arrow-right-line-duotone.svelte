<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x0q6h9bqn"/><path class="p9c0hjbwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-right-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p9c0hjbwt) {
  d: path("M12 8.5L15 12L9 19");
}

:global(.x0q6h9bqn) {
  d: path("M9 5L15 12L9 19");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
