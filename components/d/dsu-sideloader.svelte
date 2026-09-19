<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zvmzeo_nw"/><path class="p1acnqbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dsu-sideloader" {...props}></Icon>
<style>
:global(.p1acnqbyi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.07 25.07L24 30l4.93-4.93M24 30V18");
}

:global(.zvmzeo_nw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34 4.5H14a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h20a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2");
}

</style>
