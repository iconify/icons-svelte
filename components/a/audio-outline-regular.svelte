<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w74_pkbuu"/><path class="nj-oiubfo"/><path class="r7xk8o29f"/><path class="sunqexbsa"/><path class="om2raabrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:audio-outline-regular" {...props}></Icon>
<style>
:global(.nj-oiubfo) {
  d: path("M8 7v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.om2raabrv) {
  d: path("M20 10v4");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.sunqexbsa) {
  d: path("M16 7v10");
}

:global(.w74_pkbuu) {
  d: path("M4 10v4");
}

</style>
