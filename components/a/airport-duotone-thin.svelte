<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="etg-cfc2o"/><path class="m211msb-t"/><path class="ymhw07_9a"/><path class="yomj0bbqc"/><path class="ay19-ob6x"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:airport-duotone-thin" {...props}></Icon>
<style>
:global(.ay19-ob6x) {
  d: path("m6 9 4.5 -4.5h3L18 9");
}

:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.etg-cfc2o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 21V9h6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m211msb-t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 9 4.5 -4.5h3L18 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ymhw07_9a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yomj0bbqc) {
  d: path("M9 21V9h6v12");
}

</style>
