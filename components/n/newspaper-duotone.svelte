<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h-eb7n6ec"/><path class="pno2i2rdz"/><path class="y6o1pvbgv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:newspaper-duotone" {...props}></Icon>
<style>
:global(.h-eb7n6ec) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 6C7 3.7909 8.7909 2 11 2L18 2C20.2091 2 22 3.7909 22 6L22 18C22 20.2091 20.2091 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 11C2 9.3431 3.3431 8 5 8L7 8L7 6Z");
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pno2i2rdz) {
  fill: currentColor;
  d: path("M2 11C2 9.3431 3.3431 8 5 8L7 8L7 22L6 22C3.7909 22 2 20.2091 2 18L2 11Z");
  stroke: none;
}

:global(.y6o1pvbgv) {
  d: path("M12 8L17 8M12 12L17 12M12 16L15 16");
}

</style>
