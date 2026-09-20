<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aeyekmbly"/><path class="bo51iypxr"/><path class="n53lfdc0t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:confidence-outline-regular" {...props}></Icon>
<style>
:global(.aeyekmbly) {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.n53lfdc0t) {
  d: path("M16 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
