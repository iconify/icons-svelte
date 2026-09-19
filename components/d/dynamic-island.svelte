<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="dviarkb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dynamic-island" {...props}></Icon>
<style>
:global(.dviarkb8a) {
  width: 41px;
  height: 17.872px;
  x: 3.5px;
  y: 15.629px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.936px;
  ry: 8.936px;
}

</style>
