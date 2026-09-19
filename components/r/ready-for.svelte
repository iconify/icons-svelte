<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="mgvxwttbq"/><rect class="q37swqbcg"/><rect class="mi366nkdl"/><rect class="pp1sinb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ready-for" {...props}></Icon>
<style>
:global(.mgvxwttbq) {
  width: 16px;
  height: 16px;
  x: 26.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.mi366nkdl) {
  width: 16px;
  height: 16px;
  x: 26.5px;
  y: 26.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.pp1sinb3m) {
  width: 16px;
  height: 16px;
  x: 5.5px;
  y: 26.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.q37swqbcg) {
  width: 16px;
  height: 16px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>
