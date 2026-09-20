<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vefr08bem"/><path class="h8g0xgbot"/><path class="v-5f_sb8n"/><path class="px1u_4qiq"/><path class="sup6ccdkk"/><path class="x26a8iq1c"/><path class="it83nbbll"/><path class="dng5kz1zs"/><path class="i-58-pnpd"/><path class="elm0fn4gd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:offset-duotone-thin" {...props}></Icon>
<style>
:global(.dng5kz1zs) {
  d: path("M10 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.elm0fn4gd) {
  d: path("M19 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.h8g0xgbot) {
  fill: currentColor;
  d: path("M10 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i-58-pnpd) {
  d: path("M16 8v8");
}

:global(.it83nbbll) {
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.px1u_4qiq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sup6ccdkk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v-5f_sb8n) {
  fill: currentColor;
  d: path("M19 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vefr08bem) {
  fill: currentColor;
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x26a8iq1c) {
  d: path("M2 12h20");
}

</style>
