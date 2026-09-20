<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o48nut9qz"/><path class="n1ehof7re"/><path class="kr_5zj0-c"/><path class="yuprwp_zi"/><path class="bcd4ip6hz"/><path class="uk0rveqaj"/><path class="fgsu10bod"/><path class="maut9lbea"/><path class="mpg95hbwb"/><path class="ipv0cebdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:diversity-mmr-duotone-regular" {...props}></Icon>
<style>
:global(.bcd4ip6hz) {
  fill: currentColor;
  d: path("M13 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fgsu10bod) {
  d: path("M7 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ipv0cebdm) {
  d: path("M13 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.kr_5zj0-c) {
  fill: currentColor;
  d: path("M4 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.maut9lbea) {
  d: path("M4 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.mpg95hbwb) {
  d: path("M15 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.n1ehof7re) {
  fill: currentColor;
  d: path("M7 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.o48nut9qz) {
  fill: currentColor;
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uk0rveqaj) {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.yuprwp_zi) {
  fill: currentColor;
  d: path("M15 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
