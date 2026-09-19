<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ewvsp636c"/><path class="hxffalbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bluebeam" {...props}></Icon>
<style>
:global(.ewvsp636c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 17.833h12.333v12.333H17.833z");
}

:global(.hxffalbqi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.667 36.333V5.5H5.5v37h37v-37H17.833v6.167h18.5v24.667z");
}

</style>
