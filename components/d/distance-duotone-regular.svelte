<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ld7zhcybq"/><path class="cw9gc0jvg"/><path class="z75_46b2g"/><path class="u_41jqbcx"/><path class="tvvl11btt"/><path class="veni6hbgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:distance-duotone-regular" {...props}></Icon>
<style>
:global(.cw9gc0jvg) {
  fill: currentColor;
  d: path("M16 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ld7zhcybq) {
  fill: currentColor;
  d: path("M4 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tvvl11btt) {
  d: path("m7.5 16.5 9 -9");
}

:global(.u_41jqbcx) {
  d: path("M4 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.veni6hbgn) {
  d: path("M16 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.z75_46b2g) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7.5 16.5 9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
