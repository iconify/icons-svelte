<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jon3jyusz"/><path class="rencte-ct"/><path class="x4nz41duv"/><path class="tdux9oy4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:game-skin-duotone-regular" {...props}></Icon>
<style>
:global(.jon3jyusz) {
  fill: currentColor;
  d: path("m3 9 5 -5h8l5 5 -4 4v7H7v-7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rencte-ct) {
  fill: currentColor;
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tdux9oy4s) {
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.x4nz41duv) {
  d: path("m3 9 5 -5h8l5 5 -4 4v7H7v-7Z");
}

</style>
