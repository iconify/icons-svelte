<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="d9ku91bpu"/><path class="itqd-x1ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mediapart" {...props}></Icon>
<style>
:global(.d9ku91bpu) {
  width: 31.2px;
  height: 39px;
  x: 8.4px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.95px;
}

:global(.itqd-x1ra) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.48 9.38h9.2m-9.2 7.32h9.2m-9.2 7.31h9.2m-9.2 7.32h9.2m-9.2 7.31h9.2m4.61-29.26h9.21m-9.21 7.32h9.21m-9.21 7.31h9.21m-9.21 7.32h9.21m-9.21 7.31h9.21");
}

</style>
