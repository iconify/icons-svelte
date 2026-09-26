<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="epchynlxc"/><path class="e9g8fgbfl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:monitor-sharp-fill" {...props}></Icon>
<style>
:global(.e9g8fgbfl) {
  d: path("M12 15L12 20M7 20L17 20");
}

:global(.epchynlxc) {
  fill: currentColor;
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 16C23 16.5523 22.5523 17 22 17L2 17C1.4477 17 1 16.5523 1 16L1 4C1 3.4477 1.4477 3 2 3Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
