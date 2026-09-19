<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jml7h19dk"/><path class="npv61hk0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:eboox" {...props}></Icon>
<style>
:global(.jml7h19dk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.268v23.243h14.511L24 38.974l4.989-3.463H43.5V12.268");
}

:global(.npv61hk0x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.765 9.026L24 11.331v20.521L8.765 29.547zm30.469 0L24 11.331v20.521l15.234-2.305z");
}

</style>
