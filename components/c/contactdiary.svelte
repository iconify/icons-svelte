<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="nmshnxbeg"/><path class="ed9yw-btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:contactdiary" {...props}></Icon>
<style>
:global(.ed9yw-btx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.41 7.029V4.5m19.18 2.529V4.5M7.5 16.947h33m-25.482 8.937h18.834m-18.834 7.57h12.989");
}

:global(.nmshnxbeg) {
  width: 33px;
  height: 36.471px;
  x: 7.5px;
  y: 7.029px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
