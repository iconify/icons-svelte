<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y0e3bdi2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:linxo" {...props}></Icon>
<style>
:global(.y0e3bdi2b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 27.562l11.172-10.455l13.53 14.042L43.5 16.851");
}

</style>
