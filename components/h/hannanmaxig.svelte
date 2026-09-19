<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z9htyobzz"/><path class="i-1xzgb2t"/><path class="edg987bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hannanmaxig" {...props}></Icon>
<style>
:global(.edg987bfw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.66 10.178L31.98 24l5.32-7.68m0 0v15.359M10.7 16.32v15.359M21.34 24H10.699");
}

:global(.i-1xzgb2t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.32 5.571l13.3 7.679v21.5L24 45.5l-2.66-1.536V10.177");
}

:global(.z9htyobzz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.68 42.429L5.38 34.75v-21.5L24 2.5l2.66 1.536v33.787");
}

</style>
