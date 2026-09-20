<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d73irqbjb"/><path class="lpyhhqy-h"/><path class="efk3feo1w"/><path class="bt_2bvgpa"/><path class="giopbjb9g"/><path class="h_alycbda"/><path class="lb5uptbbe"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:grass-duotone-thin" {...props}></Icon>
<style>
:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d73irqbjb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 19v-7l3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.efk3feo1w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 19v-7l3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.giopbjb9g) {
  d: path("M5 19v-7l3 -3");
}

:global(.h_alycbda) {
  d: path("M10 19v-9l3 -3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lb5uptbbe) {
  d: path("M16 19v-7l3 -3");
}

:global(.lpyhhqy-h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 19v-9l3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

</style>
