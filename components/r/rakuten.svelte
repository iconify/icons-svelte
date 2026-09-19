<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dxydvusxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:rakuten" {...props}></Icon>
<style>
:global(.dxydvusxf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.153 37.816L11.12 42.503l-5.273-4.688zM13.98 32.053V5.497h8.875c5.12 0 9.216 3.983 9.216 8.962s-4.096 8.963-9.216 8.963h-8.874m9.208-.008l8.54 8.307");
}

</style>
