<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ckogh6bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:downloads" {...props}></Icon>
<style>
:global(.ckogh6bmd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.236 42.5H8.764M24 33.924V5.5M12.287 22.211L24 33.924l11.713-11.713");
}

</style>
