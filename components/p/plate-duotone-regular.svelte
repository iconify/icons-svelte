<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gfzmy-bgb"/><path class="gcurcebny"/><path class="r3faxubne"/><path class="ws1d0fbts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plate-duotone-regular" {...props}></Icon>
<style>
:global(.gcurcebny) {
  d: path("M6 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.gfzmy-bgb) {
  fill: currentColor;
  d: path("M6 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
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

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.ws1d0fbts) {
  d: path("M20 4v16");
}

</style>
