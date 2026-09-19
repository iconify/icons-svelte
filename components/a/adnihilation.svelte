<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="wsb9zacet"/><path class="xqsc8ec1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:adnihilation" {...props}></Icon>
<style>
:global(.wsb9zacet) {
  width: 39px;
  height: 24.285px;
  x: 4.5px;
  y: 11.857px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.xqsc8ec1g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.057 15.15l23.161 17.01m-12.35-17.515l3.097 18.852m-14.703-7.328l25.001-3.563m-3.933-3.872L15.641 30.448");
}

</style>
