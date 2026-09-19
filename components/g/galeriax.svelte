<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vipj2xk1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:galeriax" {...props}></Icon>
<style>
:global(.vipj2xk1b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28 20L42.5 5.5m-37 37L20 28m8 0l14.5 14.5m-37-37L20 20");
}

</style>
