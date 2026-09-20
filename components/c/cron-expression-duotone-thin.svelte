<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tu3bv3eig"/><path class="yoftwf7ei"/><path class="u0f6w1z_e"/><path class="p3wll6__i"/><path class="lt5vylzgx"/><path class="ca7cldnps"/><path class="i1q2tccms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cron-expression-duotone-thin" {...props}></Icon>
<style>
:global(.ca7cldnps) {
  d: path("M12 18v2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i1q2tccms) {
  d: path("M18 18v2.5");
}

:global(.lt5vylzgx) {
  d: path("M6 18v2.5");
}

:global(.p3wll6__i) {
  d: path("M12 9h3.5");
}

:global(.tu3bv3eig) {
  fill: currentColor;
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u0f6w1z_e) {
  d: path("M12 6v3");
}

:global(.yoftwf7ei) {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
}

</style>
