<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wzbfwmmsu"/><circle class="gekx6zb3h"/><path class="k5a5v1fkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:broken-age" {...props}></Icon>
<style>
:global(.gekx6zb3h) {
  cx: 24px;
  cy: 24px;
  r: 7.531px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.k5a5v1fkw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.794 24L24 9.794L38.206 24L24 38.206z");
}

:global(.wzbfwmmsu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.821 2.5l15.548 5.464L45.5 22.821l-5.464 15.548L25.179 45.5L9.631 40.036L2.5 25.179L7.964 9.631z");
}

</style>
