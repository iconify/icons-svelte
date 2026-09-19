<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kt_ridfzh"/><path class="rvno_8b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:j-and-t-express" {...props}></Icon>
<style>
:global(.kt_ridfzh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.829 18.163l-3.147 11.959H4.5m28.442 0l2.848-11.959m-6.572 0H43.5m-16.269 5.695c-5.125 10.25-15.375 3.416-6.264-1.14");
}

:global(.rvno_8b-t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.231 30.122l-7.414-9.681q-2.266-3.417 5.706-2.278");
}

</style>
