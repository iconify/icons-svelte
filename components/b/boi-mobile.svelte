<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lxw8b5bih"/><path class="ppyhmeb-r"/><rect class="fi-ci-bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:boi-mobile" {...props}></Icon>
<style>
:global(.fi-ci-bwg) {
  width: 6.625px;
  height: 10px;
  x: 23.984px;
  y: 19px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.313px;
  ry: 3.313px;
}

:global(.lxw8b5bih) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M33.207 19v10");
}

:global(.ppyhmeb-r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.918 24a2.5 2.5 0 0 1 0 5h-4.125V19h4.125a2.5 2.5 0 0 1 0 5m0 0h-4.125");
}

</style>
