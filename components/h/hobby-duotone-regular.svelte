<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pbbm_cbbc"/><path class="uw6x37bpc"/><path class="x2r2-hbds"/><path class="ygnemt3bx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hobby-duotone-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pbbm_cbbc) {
  fill: currentColor;
  d: path("M12 20c-4 -3 -9 -7 -7 -11.5 1.5 -3 5 -2 7 1 2 -3 5.5 -4 7 -1C21 13 16 17 12 20");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uw6x37bpc) {
  d: path("M12 20c-4 -3 -9 -7 -7 -11.5 1.5 -3 5 -2 7 1 2 -3 5.5 -4 7 -1C21 13 16 17 12 20");
}

:global(.x2r2-hbds) {
  d: path("m8 4 2 -2");
}

:global(.ygnemt3bx) {
  d: path("m16 4 -2 -2");
}

</style>
