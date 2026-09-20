<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w18s0ubfz"/><path class="k8s3elbfa"/><path class="vdr97q0tl"/><path class="ml_1ohb0q"/><path class="byucpp7wg"/><path class="kamdbib6v"/><path class="v-q4myyjv"/><path class="n2ya_p02p"/><path class="h5yksf4iw"/><path class="e3fkgnlsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-desk-duotone-regular" {...props}></Icon>
<style>
:global(.byucpp7wg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 16h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e3fkgnlsf) {
  d: path("M13 16h7");
}

:global(.h5yksf4iw) {
  d: path("M13 12h7");
}

:global(.k8s3elbfa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kamdbib6v) {
  d: path("M2 7h20");
}

:global(.ml_1ohb0q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n2ya_p02p) {
  d: path("M13 7v13h7V7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v-q4myyjv) {
  d: path("M4 7v13");
}

:global(.vdr97q0tl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 7v13h7V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w18s0ubfz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 7h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
