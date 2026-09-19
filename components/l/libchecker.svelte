<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="fa0zw9bxz"/><rect class="lws4t0buo"/><path class="dexselfgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:libchecker" {...props}></Icon>
<style>
:global(.dexselfgj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.3 5.5h3.4v5h-3.4zm6 0h3.4v5h-3.4zm-12 0h3.4v5h-3.4zm6 32h3.4v5h-3.4zm6 0h3.4v5h-3.4zm-12 0h3.4v5h-3.4zm21.2-15.2h5v3.4h-5zm0 6h5v3.4h-5zm0-12h5v3.4h-5zm-32 6h5v3.4h-5zm0 6h5v3.4h-5zm0-12h5v3.4h-5z");
}

:global(.fa0zw9bxz) {
  width: 27px;
  height: 27px;
  x: 10.5px;
  y: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.603px;
}

:global(.lws4t0buo) {
  width: 11px;
  height: 11px;
  x: 18.5px;
  y: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.69px;
}

</style>
