<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kzkxocb9k"/><path class="rbn06sbse"/><circle class="ebw07nbgg"/><path class="i4fm-d96k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:keep-screen-on" {...props}></Icon>
<style>
:global(.ebw07nbgg) {
  cx: 33.98px;
  cy: 34.146px;
  r: 8.518px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i4fm-d96k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.98 29.723v4.423m2.501 2.565l-2.501-2.565");
}

:global(.kzkxocb9k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.87 40.958H13.443A3.454 3.454 0 0 1 9.985 37.5V20.51a3.454 3.454 0 0 1 3.458-3.458H33.89a3.454 3.454 0 0 1 3.457 3.458v5.813");
}

:global(.rbn06sbse) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.82 17.052v-3.354a6.85 6.85 0 0 1 6.847-6.847c1.883 0 3.607.77 4.836 2.01a6.8 6.8 0 0 1 2.01 4.837v3.354");
}

</style>
