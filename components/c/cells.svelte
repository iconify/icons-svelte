<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tsx-iidad"/><circle class="bet3xg9mj"/><circle class="b19ws4gce"/><circle class="jorq9bcyb"/><circle class="d48dgjr0a"/><circle class="x_ic6eb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cells" {...props}></Icon>
<style>
:global(.b19ws4gce) {
  cx: 29.06px;
  cy: 14.238px;
  r: 2.022px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.bet3xg9mj) {
  cx: 24px;
  cy: 6.522px;
  r: 2.022px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.d48dgjr0a) {
  cx: 14.049px;
  cy: 18.371px;
  r: 2.022px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jorq9bcyb) {
  cx: 33.769px;
  cy: 20.911px;
  r: 2.022px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tsx-iidad) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 32.507l9.77-6.995v-2.578m-9.77.871l5.06-4.228V16.26M24 29.975l-9.95-7.362v-2.22M24 21.54l-4.879-3.76v-4.313M8.444 43.5c3.438-4.346 6.43-7.057 11.936-7.057M24 34.71l1.733 1.732L24 38.175l-1.733-1.733zm-1.733 1.733h-8.082m13.435 0c5.506 0 8.498 2.711 11.936 7.057m-13.823-7.057h8.082M24 38.176v2.374m0-5.841V8.545");
}

:global(.x_ic6eb8x) {
  cx: 19.121px;
  cy: 11.444px;
  r: 2.022px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
