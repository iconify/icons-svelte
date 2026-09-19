<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ixwm99e5c"/><path class="ks72jbyxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:alarmy" {...props}></Icon>
<style>
:global(.ixwm99e5c) {
  cx: 23.945px;
  cy: 24.129px;
  r: 18.411px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ks72jbyxx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.656 15.009a5.754 5.754 0 1 1 8.598-7.647m15.938.302a5.754 5.754 0 1 1 8.158 8.002M24.385 13.1v11.873l6.638 5.648");
}

</style>
