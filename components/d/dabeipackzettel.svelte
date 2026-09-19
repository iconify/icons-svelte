<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="emrxkfbid"/><path class="xc17i9b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dabeipackzettel" {...props}></Icon>
<style>
:global(.emrxkfbid) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.976 24L6.179 5.5v37z");
}

:global(.xc17i9b2g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.976 24h20.846L28.396 5.5H6.179zm0 0h20.846L28.396 42.5H6.179z");
}

</style>
