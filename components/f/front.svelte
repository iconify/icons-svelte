<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="goc-kfbyz"/><circle transform="rotate(-22.5 31.251 31.251)" class="ha8mnqrjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:front" {...props}></Icon>
<style>
:global(.goc-kfbyz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.224 5.5H5.5v35.724h12.299V17.799h23.425z");
}

:global(.ha8mnqrjt) {
  cx: 31.251px;
  cy: 31.251px;
  r: 11.249px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
