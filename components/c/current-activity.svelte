<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="vs-8lefmr"/><path class="pjdgxybno"/><path class="rr4d4dbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:current-activity" {...props}></Icon>
<style>
:global(.pjdgxybno) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.857 30.128l5.578-8.647l7.001 5.982l5.956-8.47");
}

:global(.rr4d4dbaf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.238 17.858v15.66c0 4.976-3.495 8.982-7.837 8.982H13.367c-4.341 0-7.836-4.006-7.836-8.983v-17.74c0-4.977 3.495-8.983 7.837-8.983h16.68");
}

:global(.vs-8lefmr) {
  cx: 38.232px;
  cy: 9.737px;
  r: 4.237px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
