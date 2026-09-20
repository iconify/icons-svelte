<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgrfb-bqu"/><path class="sprybdcan"/><path class="xsa445osm"/><path class="w7sxxlcqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:a-record-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sprybdcan) {
  d: path("M3 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.w7sxxlcqv) {
  d: path("m18 12 3 3 -3 3");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.xsa445osm) {
  d: path("M9 15h7");
}

</style>
