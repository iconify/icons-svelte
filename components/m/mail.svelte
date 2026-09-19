<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hmq8ctw6v"/><rect class="ktu0bwb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mail" {...props}></Icon>
<style>
:global(.hmq8ctw6v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.735 15.224L24 26.072L9.265 15.224");
}

:global(.ktu0bwb7d) {
  width: 39px;
  height: 26.582px;
  x: 4.5px;
  y: 10.709px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
