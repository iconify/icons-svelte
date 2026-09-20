<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pq9ly31-r"/><path class="xq1pi7btv"/><path class="ng6jddb9r"/><path class="ayfcapvsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:consensus-outline-regular" {...props}></Icon>
<style>
:global(.ayfcapvsy) {
  d: path("M9 13a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.ng6jddb9r) {
  d: path("M18 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pq9ly31-r) {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xq1pi7btv) {
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
