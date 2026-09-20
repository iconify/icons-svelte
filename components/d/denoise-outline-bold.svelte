<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z35tx4bdc"/><path class="mqnae981n"/><path class="oifr9zbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:denoise-outline-bold" {...props}></Icon>
<style>
:global(.mqnae981n) {
  d: path("m9 11 3 3 3 -3");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z35tx4bdc) {
  d: path("m3 6 4 -4 4 4 4 -4 4 4");
}

</style>
