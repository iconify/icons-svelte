<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h1er6kbcg"/><path class="bqmtvvbnd"/><path class="boqmo37co"/><path class="amid48b6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:parallel-duotone-regular" {...props}></Icon>
<style>
:global(.amid48b6f) {
  d: path("m8 12 4 4h9");
}

:global(.boqmo37co) {
  d: path("M3 12h5l4 -4h9");
}

:global(.bqmtvvbnd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 12 4 4h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h1er6kbcg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h5l4 -4h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
