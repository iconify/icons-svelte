<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hafxviwoh"/><path class="r9_u-nf6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:google-jamboard" {...props}></Icon>
<style>
:global(.hafxviwoh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 30.5a13 13 0 1 1-13-13");
}

:global(.r9_u-nf6q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5h13v26H24zm0 13h13");
}

</style>
