<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nr15-kblk"/><rect class="malleql-h"/><path class="yvf78tbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:huawei-notepad" {...props}></Icon>
<style>
:global(.malleql-h) {
  width: 17.415px;
  height: 9.307px;
  x: 14.665px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

:global(.nr15-kblk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.08 9.897h6.764a3 3 0 0 1 3 3V39.5a3 3 0 0 1-3 3H9.157a3 3 0 0 1-3-3V12.897a3 3 0 0 1 3-3h5.507");
}

:global(.yvf78tbvz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.981 26.455h13.076");
}

</style>
