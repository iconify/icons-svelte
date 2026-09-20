<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pqype0qiq"/><path class="iyihhmx5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:echo-music" {...props}></Icon>
<style>
:global(.iyihhmx5g) {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.237 24A9.237 9.237 0 0 1 24 33.237A9.237 9.237 0 0 1 14.763 24A9.237 9.237 0 0 1 24 14.763A9.237 9.237 0 0 1 33.237 24");
}

:global(.pqype0qiq) {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.5 21.5 0 0 1 24 45.5A21.5 21.5 0 0 1 2.5 24A21.5 21.5 0 0 1 24 2.5A21.5 21.5 0 0 1 45.5 24");
}

</style>
