<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r4h1y5b9l"/><path class="lahg3nbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:file-kotlin" {...props}></Icon>
<style>
:global(.lahg3nbkl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.192 38.692H14.808V20.308h18.384L24 29.5z");
}

:global(.r4h1y5b9l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2zm-11-11l11 11");
}

</style>
