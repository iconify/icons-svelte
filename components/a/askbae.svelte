<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p8-_1ovuv"/><circle class="w8nozx66d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:askbae" {...props}></Icon>
<style>
:global(.p8-_1ovuv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.014 12.734A13 13 0 0 1 30.5 11a13 13 0 0 1 13 13a13 13 0 0 1-13 13a13 13 0 0 1-6.513-1.75");
}

:global(.w8nozx66d) {
  cx: 17.5px;
  cy: 24px;
  r: 13px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
