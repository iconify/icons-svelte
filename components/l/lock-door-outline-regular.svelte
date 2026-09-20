<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ef-jgqbdk"/><path class="k4p4tzbhq"/><path class="y_j9zzqtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lock-door-outline-regular" {...props}></Icon>
<style>
:global(.ef-jgqbdk) {
  d: path("M4 3v18h10V3Z");
}

:global(.k4p4tzbhq) {
  d: path("M17 13v6h5v-6Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y_j9zzqtv) {
  d: path("M17.5 13a2 2 0 0 1 4 0");
}

</style>
