<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0n63pb2v"/><path class="dhoelsbfc"/><path class="atvcffgcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-retrieve-outline-regular" {...props}></Icon>
<style>
:global(.atvcffgcu) {
  d: path("m11.5 8 3.5 3.5");
}

:global(.dhoelsbfc) {
  d: path("M9 7.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
