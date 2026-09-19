<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bxxb6ndav"/><circle class="p9h8wrdan"/><path class="agb5ekdfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:play-integrity-api-checker" {...props}></Icon>
<style>
:global(.agb5ekdfj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.531 35.117l-7.179-7.18");
}

:global(.bxxb6ndav) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c3.883 0 14.68-7.263 15.658-19.893v-13.48L24 4.5L8.342 10.127v13.48C8.906 35.517 19.834 43.5 24 43.5");
}

:global(.p9h8wrdan) {
  cx: 24px;
  cy: 24.044px;
  r: 5.846px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
