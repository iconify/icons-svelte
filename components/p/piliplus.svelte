<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c5dxnqa1b"/><rect class="j3s9ivbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:piliplus" {...props}></Icon>
<style>
:global(.c5dxnqa1b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.99 16.177l4.311-.012m-.266 9.604l-6.23-.007m6.306.005a4.86 4.86 0 0 0 3.2-1.361a4.86 4.86 0 0 0 1.446-3.163a4.86 4.86 0 0 0-1.063-3.31a4.86 4.86 0 0 0-3.34-1.768m-3.775.008h-.923m-1.866 9.585l-1.484 7.43m1.906-16.235l-1.485 7.43");
}

:global(.j3s9ivbxi) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
