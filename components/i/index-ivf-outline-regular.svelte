<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tu5a-bcmx"/><path class="tip34zbqw"/><path class="jt7d488ke"/><path class="m0hvambgh"/><path class="esz0ytbwn"/><path class="me177l4bh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-ivf-outline-regular" {...props}></Icon>
<style>
:global(.esz0ytbwn) {
  d: path("M8 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.jt7d488ke) {
  d: path("M13 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.m0hvambgh) {
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.me177l4bh) {
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tip34zbqw) {
  d: path("M6 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.tu5a-bcmx) {
  d: path("M3 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
