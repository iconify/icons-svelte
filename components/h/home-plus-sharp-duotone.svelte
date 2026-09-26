<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r936wd-yw"/><path class="h9ko0s7ae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:home-plus-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.h9ko0s7ae) {
  d: path("M8 23L8 15L14 15L14 23M19 1L19 9M15 5L23 5");
}

:global(.r936wd-yw) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 11L21 22C21 22.55 20.55 23 20 23L2 23C1.45 23 1 22.55 1 22L1 11C1 10.69 1.14 10.4 1.39 10.21L10.39 3.21C10.75 2.93 11.25 2.93 11.61 3.21L13 4.2856L13 11L21 11Z");
  stroke: none;
}

</style>
