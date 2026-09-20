<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jje0epbum"/><path class="kfdmhd64i"/><path class="e4btx4zel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flaky-test-outline-regular" {...props}></Icon>
<style>
:global(.e4btx4zel) {
  d: path("m21 15 -6 6");
}

:global(.jje0epbum) {
  d: path("m3 7 3 3 5 -5");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
