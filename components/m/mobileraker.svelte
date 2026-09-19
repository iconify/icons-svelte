<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m_6ld3bjw"/><path class="hwrahldnk"/><path class="ah6xeabxh"/><path class="ymy74d55z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mobileraker" {...props}></Icon>
<style>
:global(.ah6xeabxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.35 16.47l14.928 8.996L38.65 16.47L24.278 8.484z");
}

:global(.hwrahldnk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.303 20.664L24 31.581l16.697-10.917");
}

:global(.m_6ld3bjw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 26.578l18.652 12.938L42.5 26.578");
}

:global(.ymy74d55z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.018 16.975l7.906-4.043l8.058 4.043m-12.2 2.375l4.269-2.375l4.167 2.375");
}

</style>
