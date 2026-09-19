<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="trafj028l"/><path class="h9xgr0pvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lazypay" {...props}></Icon>
<style>
:global(.h9xgr0pvf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5 14.945L28.156 24L5 33.055");
}

:global(.trafj028l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.844 14.945L43 24l-23.156 9.055");
}

</style>
