<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h1d-55bch"/><path class="ym8c-xbed"/><path class="zwfc0tbtb"/><path class="u7en4tb0h"/><path class="sj1ms3civ"/><path class="mhila7bcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-quota-duotone-regular" {...props}></Icon>
<style>
:global(.h1d-55bch) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6.27 9.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mhila7bcl) {
  d: path("M20 7v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sj1ms3civ) {
  d: path("M15.27 9.28a3 3 0 1 1 -2.54 0");
}

:global(.u7en4tb0h) {
  d: path("M6.27 9.28a3 3 0 1 1 -2.54 0");
}

:global(.ym8c-xbed) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15.27 9.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zwfc0tbtb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
