<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aquqhs1ys"/><path class="x6l3q_bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:enki-2" {...props}></Icon>
<style>
:global(.aquqhs1ys) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.25L4.5 33.75h39zm0 0v13");
}

:global(.x6l3q_bvt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 33.75L24 27.25l-19.5 6.5");
}

</style>
