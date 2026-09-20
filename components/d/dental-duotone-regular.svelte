<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tbfv-yd2s"/><path class="jm7jgyogs"/><path class="vrzeiketi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dental-duotone-regular" {...props}></Icon>
<style>
:global(.jm7jgyogs) {
  d: path("M4 6a4 4 0 0 1 5 2 4 4 0 0 1 5 -2c2 4 0 13 -2.5 13C10 19 10 13 9 13s-1 6 -2.5 6C4 19 2 10 4 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tbfv-yd2s) {
  fill: currentColor;
  d: path("M4 6a4 4 0 0 1 5 2 4 4 0 0 1 5 -2c2 4 0 13 -2.5 13C10 19 10 13 9 13s-1 6 -2.5 6C4 19 2 10 4 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vrzeiketi) {
  d: path("m16 15 2 2 4 -4");
}

</style>
