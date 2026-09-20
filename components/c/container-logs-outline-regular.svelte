<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b-pphqpeq"/><path class="sfnyx4wnk"/><path class="c5cmy2bxq"/><path class="p7w9wl2eu"/><path class="rif3k096t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:container-logs-outline-regular" {...props}></Icon>
<style>
:global(.b-pphqpeq) {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.c5cmy2bxq) {
  d: path("M9 10h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p7w9wl2eu) {
  d: path("M9 13h8");
}

:global(.rif3k096t) {
  d: path("M9 16h5");
}

:global(.sfnyx4wnk) {
  d: path("M6 6v14");
}

</style>
