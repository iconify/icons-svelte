<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="hbw5_ccle"/><path class="ze3hawb4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:annotation-chart-outline-regular" {...props}></Icon>
<style>
:global(.hbw5_ccle) {
  d: path("m7 17 4 -4 4 4 4 -4");
}

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

:global(.ze3hawb4v) {
  d: path("M14 6v12");
}

</style>
