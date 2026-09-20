<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgrfb-bqu"/><path class="pesxdybze"/><path class="etqzyebuj"/><path class="y7_y8yq8z"/><path class="tb33trnmj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:inline-suggestion-outline-regular" {...props}></Icon>
<style>
:global(.etqzyebuj) {
  d: path("M13 12h2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pesxdybze) {
  d: path("M3 12h7");
}

:global(.tb33trnmj) {
  d: path("M3 18h5");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.y7_y8yq8z) {
  d: path("M18.5 12H21");
}

</style>
