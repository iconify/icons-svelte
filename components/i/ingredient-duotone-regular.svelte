<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="as04bxwqk"/><path class="zo-o-sdgc"/><path class="q059s7b6t"/><path class="cp7scyw-s"/><path class="youb8ccbq"/><path class="z9rf4z-yw"/><path class="g-a4wz-fw"/><path class="x_kkpk0ip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ingredient-duotone-regular" {...props}></Icon>
<style>
:global(.as04bxwqk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 14h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cp7scyw-s) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 14 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g-a4wz-fw) {
  d: path("M8 14a3 3 0 0 1 6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q059s7b6t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 14a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x_kkpk0ip) {
  d: path("m16 14 5 -5");
}

:global(.youb8ccbq) {
  d: path("M6 14h10");
}

:global(.z9rf4z-yw) {
  d: path("M16 14a5 5 0 0 1 -10 0");
}

:global(.zo-o-sdgc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 14a5 5 0 0 1 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
