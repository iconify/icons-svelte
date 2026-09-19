<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="gkbzx0-9v"/><path class="fumqqf1fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:launcher-alt-1" {...props}></Icon>
<style>
:global(.fumqqf1fg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.806 24.837v4.42h-7.612v-4.42m9.376-1.066L24 18.201l-5.57 5.57M12.5 8h23m0 32h-23");
}

:global(.gkbzx0-9v) {
  width: 23px;
  height: 39px;
  x: 12.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>
