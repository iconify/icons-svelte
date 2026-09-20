<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jdo7z8-qu"/><path class="w-bnpitut"/><path class="ws24-9bwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:paintbrush-outline-regular" {...props}></Icon>
<style>
:global(.jdo7z8-qu) {
  d: path("m3 21 9 -9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w-bnpitut) {
  d: path("m12 12 3 -3 4 4 -3 3Z");
}

:global(.ws24-9bwu) {
  d: path("m19 13 2 -2 -4 -4 -2 2Z");
}

</style>
