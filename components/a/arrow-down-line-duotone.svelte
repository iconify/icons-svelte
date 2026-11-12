<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sijy5cc4z"/><path class="gp0t1_y6e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-down-line-duotone" {...props}></Icon>
<style>
:global(.gp0t1_y6e) {
  d: path("M18 14L12 20L6 14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sijy5cc4z) {
  d: path("M12 4V20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
