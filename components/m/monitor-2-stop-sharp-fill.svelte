<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="oit84qbgx"/><path class="m77kogrek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:monitor-2-stop-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.m77kogrek) {
  d: path("M12 17L12 21M7 21L17 21");
}

:global(.oit84qbgx) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 2L22 2C22.5523 2 23 2.4477 23 3L23 17C23 17.5523 22.5523 18 22 18L2 18C1.4477 18 1 17.5523 1 17L1 3C1 2.4477 1.4477 2 2 2ZM9 6C8.4477 6 8 6.4477 8 7L8 13C8 13.5523 8.4477 14 9 14L15 14C15.5523 14 16 13.5523 16 13L16 7C16 6.4477 15.5523 6 15 6L9 6Z");
  stroke: none;
}

</style>
