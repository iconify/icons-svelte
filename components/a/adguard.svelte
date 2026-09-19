<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vb_uuxzdb"/><path class="fg5cg9o6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:adguard" {...props}></Icon>
<style>
:global(.fg5cg9o6z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.26 23.09l5.98 5.94l9.62-12.36");
}

:global(.vb_uuxzdb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.2 4.86L6.69 11.25V27C6.69 35.44 24 43.5 24 43.5S41.31 35.44 41.31 27V11.25L25.8 4.86a4.68 4.68 0 0 0-3.6 0");
}

</style>
