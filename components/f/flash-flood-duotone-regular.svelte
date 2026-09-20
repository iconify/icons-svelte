<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vkszfebpv"/><path class="mwgdeer7v"/><path class="h0ad5ebtk"/><path class="zmjbj80iu"/><path class="xr4pgs06d"/><path class="kry_r4p8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flash-flood-duotone-regular" {...props}></Icon>
<style>
:global(.h0ad5ebtk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 20 2.5 -2.5L8 20l2.5 -2.5L13 20l2.5 -2.5L18 20l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kry_r4p8f) {
  d: path("m3 20 2.5 -2.5L8 20l2.5 -2.5L13 20l2.5 -2.5L18 20l2.5 -2.5");
}

:global(.mwgdeer7v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 15 2.5 -2.5L8 15l2.5 -2.5L13 15l2.5 -2.5L18 15l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vkszfebpv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 4 11 6.5h2.5L11 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xr4pgs06d) {
  d: path("m3 15 2.5 -2.5L8 15l2.5 -2.5L13 15l2.5 -2.5L18 15l2.5 -2.5");
}

:global(.zmjbj80iu) {
  d: path("M13.5 4 11 6.5h2.5L11 9");
}

</style>
