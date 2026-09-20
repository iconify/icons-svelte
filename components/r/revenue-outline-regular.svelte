<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o610cu0jy"/><path class="u_pwg_bmr"/><path class="lev20-kjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:revenue-outline-regular" {...props}></Icon>
<style>
:global(.lev20-kjj) {
  d: path("m14 17 2.5 -2.5 2 2L22 13");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o610cu0jy) {
  d: path("M2.5 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.u_pwg_bmr) {
  d: path("M7 10.5v3");
}

</style>
