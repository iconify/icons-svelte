<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sl0tqnboi"/><path class="yf0ac-1wm"/><path class="vrzeiketi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:freshness-check-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sl0tqnboi) {
  d: path("M4 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.vrzeiketi) {
  d: path("m16 15 2 2 4 -4");
}

:global(.yf0ac-1wm) {
  d: path("M10 9v3h3");
}

</style>
