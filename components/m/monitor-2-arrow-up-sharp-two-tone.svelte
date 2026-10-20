<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g7qcrlbrp"/><path class="mon9-r75g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:monitor-2-arrow-up-sharp-two-tone" {...props}></Icon>
<style>
:global(.g7qcrlbrp) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 2L22 2C22.5523 2 23 2.4477 23 3L23 17C23 17.5523 22.5523 18 22 18L2 18C1.4477 18 1 17.5523 1 17L1 3C1 2.4477 1.4477 2 2 2Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.mon9-r75g) {
  d: path("M2 3L22 3L22 17L2 17ZM12 17L12 21M7 21L17 21M12 14L12 7M8.7071 10.2929L12 7L15.2929 10.2929");
}

</style>
