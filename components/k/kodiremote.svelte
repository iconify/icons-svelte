<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(45 23.999 24)" class="b7ytelbju"/><path class="ffg7wlbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kodiremote" {...props}></Icon>
<style>
:global(.b7ytelbju) {
  width: 29.97px;
  height: 29.97px;
  x: 9.02px;
  y: 9.02px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

:global(.ffg7wlbuc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.83 37.02V15.16H31.8v7.71L16.74 37.93m17.84-3.32l-7.26-7.25");
}

</style>
