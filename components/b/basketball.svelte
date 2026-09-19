<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="gp2cf5bkp"/><path class="pjggdt7de"/><path class="p7l7dxugr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:basketball" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.gp2cf5bkp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.558 25.58c7.417-13.344 27.41-17.984 42.182-7.267");
}

:global(.p7l7dxugr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.55 3.485c-3.932 8.108-2.562 29.798 17.523 38.948M6.449 11.579c5.8.126 7.085 6.666 5.632 12.592s-3.766 9.363-.71 17.231");
}

:global(.pjggdt7de) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.966 2.59c-6.046 1.91-8.5 14.547 2.96 21.292c6.691 3.939 9.018 1.267 15.506 6.827");
}

</style>
