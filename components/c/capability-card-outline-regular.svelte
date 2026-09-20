<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d3xn50bni"/><path class="znz1wcbkt"/><path class="gte-olbep"/><path class="jz3tcofhe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:capability-card-outline-regular" {...props}></Icon>
<style>
:global(.d3xn50bni) {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.gte-olbep) {
  d: path("M10 8v3.5");
}

:global(.jz3tcofhe) {
  d: path("M14 8v3.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.znz1wcbkt) {
  d: path("M8 14a2.5 2.5 0 0 1 2.5 -2.5h3A2.5 2.5 0 0 1 16 14a2.5 2.5 0 0 1 -2.5 2.5h-3A2.5 2.5 0 0 1 8 14");
}

</style>
