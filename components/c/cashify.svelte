<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fmiyufzhm"/><path class="ki76r6_xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cashify" {...props}></Icon>
<style>
:global(.fmiyufzhm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14 19.121l8.308 8.166L34 15.723");
}

:global(.ki76r6_xg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.203 39.203c-8.396 8.396-22.01 8.396-30.406 0s-8.396-22.01 0-30.406m30.406 0c-8.397-8.396-22.01-8.396-30.406 0m30.406 30.406");
}

</style>
