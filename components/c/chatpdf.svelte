<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lpnay_b9u"/><path class="t4p-svbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:chatpdf" {...props}></Icon>
<style>
:global(.lpnay_b9u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5C13.783 5.5 5.5 13.783 5.5 24S13.783 42.5 24 42.5L42.5 24V5.5z");
}

:global(.t4p-svbok) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5V28c0-2.216 1.784-4 4-4h14.5");
}

</style>
