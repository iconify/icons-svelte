<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lvb3nebis"/><path class="duuhr1boc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-pull-request-create-arrow-sharp-fill" {...props}></Icon>
<style>
:global(.duuhr1boc) {
  fill: currentColor;
  d: path("M6 2C8.0711 2 10 3.9289 10 6C10 8.0711 8.0711 10 6 10C3.9289 10 2 8.0711 2 6C2 3.9289 3.9289 2 6 2Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.lvb3nebis) {
  d: path("M6 22L6 8M13.1465 6L18 6L18 13M15.0858 3.7071L12.7929 6L15.0858 8.2929M18.5 15L18.5 22M15 18.5L22 18.5");
}

</style>
