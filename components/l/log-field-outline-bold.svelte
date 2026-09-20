<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jd_dotbnq"/><path class="h2fnwccfy"/><path class="gwl0nvbom"/><path class="mimgzlb8r"/><path class="c6uw-ccfl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:log-field-outline-bold" {...props}></Icon>
<style>
:global(.c6uw-ccfl) {
  d: path("M7 14h10");
}

:global(.gwl0nvbom) {
  d: path("M6 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.h2fnwccfy) {
  d: path("M7 6h10");
}

:global(.jd_dotbnq) {
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
}

:global(.mimgzlb8r) {
  d: path("M11.5 10H17");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
