<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="z6_a1yqbp"/><circle class="lpd-10b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:compose-material-catalog" {...props}></Icon>
<style>
:global(.lpd-10b9h) {
  cx: 29.517px;
  cy: 29.517px;
  r: 12.982px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z6_a1yqbp) {
  width: 24.017px;
  height: 24.017px;
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
