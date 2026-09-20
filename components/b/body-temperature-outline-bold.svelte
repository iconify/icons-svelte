<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mwf5pf3ps"/><path class="o1d_6eb1p"/><path class="ghpezkxlh"/><path class="ffv1x3til"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:body-temperature-outline-bold" {...props}></Icon>
<style>
:global(.ffv1x3til) {
  d: path("M15 4a6 6 0 0 1 0 12");
}

:global(.ghpezkxlh) {
  d: path("M15 7a3 3 0 0 1 0 6");
}

:global(.mwf5pf3ps) {
  d: path("M9 4v11");
}

:global(.o1d_6eb1p) {
  d: path("M6 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
