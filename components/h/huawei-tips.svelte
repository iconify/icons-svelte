<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yp5wmx6nl"/><circle class="jmghjrbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:huawei-tips" {...props}></Icon>
<style>
:global(.jmghjrbrd) {
  cx: 30.244px;
  cy: 16.176px;
  r: 1.705px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yp5wmx6nl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.28 7.896L6.436 27.375L27.72 42.5l13.843-19.48L37.999 5.5zm7.191 12.524l-6.863 9.657");
}

</style>
