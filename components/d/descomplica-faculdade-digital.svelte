<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yd-db6b4y"/><path class="mbz06xban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:descomplica-faculdade-digital" {...props}></Icon>
<style>
:global(.mbz06xban) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.75 21.69a6.07 6.07 0 0 0-6.05-6.05h0a6.07 6.07 0 0 0-6.051 6.05v3.934a6.07 6.07 0 0 0 6.05 6.05h0a6.07 6.07 0 0 0 6.051-6.05m-.002 6.049V7.47");
}

:global(.yd-db6b4y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.224 11.212L41.776 5.5v37L6.224 35.83Z");
}

</style>
