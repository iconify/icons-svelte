<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k187sabpz"/><path class="kpavcn10r"/><path class="o70nty8gv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:allergen-outline-regular" {...props}></Icon>
<style>
:global(.k187sabpz) {
  d: path("M2 11h20");
}

:global(.kpavcn10r) {
  d: path("M21 11a9 9 0 0 1 -18 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o70nty8gv) {
  d: path("m12 2 7 7H5Z");
}

</style>
