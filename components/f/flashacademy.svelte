<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pcj-_rigq"/><circle class="wd9i8zbsg"/><path class="xfgcmxqle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:flashacademy" {...props}></Icon>
<style>
:global(.pcj-_rigq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 4.5h14a5.5 5.5 0 1 1 0 11H17a5.5 5.5 0 1 1 0-11");
}

:global(.wd9i8zbsg) {
  cx: 31px;
  cy: 24px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xfgcmxqle) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 18.5za5.5 5.5 0 0 1 5.5 5.5v14a5.5 5.5 0 1 1-11 0V24a5.5 5.5 0 0 1 5.5-5.5");
}

</style>
