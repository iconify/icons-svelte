<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nizbrguot"/><path class="mypzt1bhf"/><path class="dk2_9r6pl"/><path class="k7g3kwg9m"/><path class="qp1vb3rzl"/><path class="o8od38cnm"/><path class="of_dlbc-j"/><path class="pma7fkjmg"/><path class="n0hr0gbrt"/><path class="gf_3phz1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flower-bed-duotone-regular" {...props}></Icon>
<style>
:global(.dk2_9r6pl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gf_3phz1c) {
  d: path("M16 14v4");
}

:global(.k7g3kwg9m) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mypzt1bhf) {
  fill: currentColor;
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n0hr0gbrt) {
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nizbrguot) {
  fill: currentColor;
  d: path("M6 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.of_dlbc-j) {
  d: path("M6 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.pma7fkjmg) {
  d: path("M8 11v7");
}

:global(.qp1vb3rzl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
