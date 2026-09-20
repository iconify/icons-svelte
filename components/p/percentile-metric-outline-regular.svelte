<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="z29yzbtbb"/><path class="xmro9gb_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:percentile-metric-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.xmro9gb_f) {
  d: path("M15 8v10");
}

:global(.z29yzbtbb) {
  d: path("m6 17 3 -3 3 -3 3 3 3 3");
}

</style>
