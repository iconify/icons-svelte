<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="ktb6cfbzg"/><path class="ciuliaccs"/><circle class="otyepqbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:huawei-photos" {...props}></Icon>
<style>
:global(.ciuliaccs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.597 35.65c8.102-19.27 19.18-7.636 26.42.184c.558.603 2.446-1.406 2.446-1.406");
}

:global(.ktb6cfbzg) {
  width: 37px;
  height: 33.82px;
  x: 5.5px;
  y: 7.09px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.otyepqbrf) {
  cx: 31.766px;
  cy: 18.19px;
  r: 2.878px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
