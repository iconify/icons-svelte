<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dz3zu-bor"/><path class="a_uq5jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:labamu" {...props}></Icon>
<style>
:global(.a_uq5jbwx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 42.5v-37H42.5z");
}

:global(.dz3zu-bor) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 30.167H5.5L42.5 5.5v24.667H26.056");
}

</style>
