<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c78la1bmh"/><circle class="n66gzcbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nicehash" {...props}></Icon>
<style>
:global(.c78la1bmh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24a18.5 18.5 0 0 0 37 0H30.016a6.016 6.016 0 0 1-12.032 0ZM24 5.5h18.251v12.484H24z");
}

:global(.n66gzcbke) {
  cx: 11.742px;
  cy: 11.742px;
  r: 6.242px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
