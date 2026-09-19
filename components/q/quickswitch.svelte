<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="k2p_ujbyr"/><rect class="p48m-sb-m"/><rect class="rn5b5cb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:quickswitch" {...props}></Icon>
<style>
:global(.k2p_ujbyr) {
  width: 17.249px;
  height: 33.211px;
  x: 15.375px;
  y: 7.395px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.065px;
}

:global(.p48m-sb-m) {
  width: 7.195px;
  height: 28.398px;
  x: 4.5px;
  y: 9.8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.065px;
}

:global(.rn5b5cb4i) {
  width: 7.195px;
  height: 28.398px;
  x: 36.305px;
  y: 9.8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.065px;
}

</style>
