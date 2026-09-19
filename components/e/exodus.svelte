<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vu2blbwyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:exodus" {...props}></Icon>
<style>
:global(.vu2blbwyk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.96 5.5L24 21.46L8.04 5.5M42.5 39.96L26.54 24L42.5 8.04M8.04 42.5L24 26.54L39.96 42.5M5.5 8.04L21.46 24L5.5 39.96");
}

</style>
