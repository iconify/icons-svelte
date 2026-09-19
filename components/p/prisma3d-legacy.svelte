<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yu2wv8rey"/><path class="q775hibnu"/><path class="sj0kfebzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:prisma3d-legacy" {...props}></Icon>
<style>
:global(.q775hibnu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.436a6.863 6.863 0 1 1-13.727 0a6.863 6.863 0 0 1 13.727 0");
}

:global(.sj0kfebzk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.676 31.515v7.843h3.922");
}

:global(.yu2wv8rey) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 36.739l16.69-9.637m1.23-2.154V5.7m1.228 21.401l7.387 4.265m1.28-1.326L22.42 12.9L10.735 33.138h19.374");
}

</style>
