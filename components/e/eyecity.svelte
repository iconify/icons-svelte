<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="p0h_trzsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:eyecity" {...props}></Icon>
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

:global(.p0h_trzsr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.342 9.5a3.843 3.843 0 0 0 0 7.686q.452-.006.893-.116A12 12 0 0 0 12 24c0 6.627 5.373 12 12 12s12-5.372 12-12s-5.372-12-12-12a12 12 0 0 0-6.93 2.235q.11-.44.116-.893A3.843 3.843 0 0 0 13.342 9.5");
}

</style>
