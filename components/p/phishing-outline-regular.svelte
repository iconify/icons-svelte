<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a51oytv8p"/><path class="jz3tfobnp"/><path class="ur5cuwbiy"/><path class="op8_xbqqk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:phishing-outline-regular" {...props}></Icon>
<style>
:global(.a51oytv8p) {
  d: path("M13 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.jz3tfobnp) {
  d: path("M15 6v9.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.op8_xbqqk) {
  d: path("M6 11v4.5");
}

:global(.ur5cuwbiy) {
  d: path("M15 15.5a4.5 4.5 0 0 1 -9 0");
}

</style>
