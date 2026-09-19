<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u_vcnxv7h"/><path class="ovpo1sb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:docus" {...props}></Icon>
<style>
:global(.ovpo1sb1e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18 33V15h4.06A7.88 7.88 0 0 1 30 22.87v2.25A7.88 7.88 0 0 1 22.09 33Z");
}

:global(.u_vcnxv7h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 15v26.55a2 2 0 0 0 1.95 2h27.3a2 2 0 0 0 2-2V6.45a2 2 0 0 0-2-1.95H18");
}

</style>
