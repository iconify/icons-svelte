<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yypf9mbbm"/><path class="oy27h2b6d"/><rect class="cpr0-1bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ecostream" {...props}></Icon>
<style>
:global(.cpr0-1bcb) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6px;
  ry: 6px;
}

:global(.oy27h2b6d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.259 20.348V34.2h10.679a5.25 5.25 0 1 0 0-10.5H25.92");
}

:global(.yypf9mbbm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.259 13.2h8.662a5.25 5.25 0 1 1 0 10.5H17.26");
}

</style>
