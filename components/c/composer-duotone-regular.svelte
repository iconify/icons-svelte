<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ym3w5ba4s"/><path class="murw5tb-p"/><path class="mi7pnccmc"/><path class="dpr_gnqpq"/><path class="h0hlbvfqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:composer-duotone-regular" {...props}></Icon>
<style>
:global(.dpr_gnqpq) {
  d: path("m14.5 14.5 4 -4");
}

:global(.h0hlbvfqt) {
  d: path("M15.5 10.5h3v3");
}

:global(.mi7pnccmc) {
  d: path("M6 10v4");
}

:global(.murw5tb-p) {
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ym3w5ba4s) {
  fill: currentColor;
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
