<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="k3cnofwci"/><path class="c64g-2e7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kanal-d" {...props}></Icon>
<style>
:global(.c64g-2e7d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.943 42.5c19.25-2.524 25.728-14.197 22.598-22.864c-.536-1.484-5.67-13.98-26.578-14.136l2.728 9.333a9.374 9.374 0 0 1 7.527 9.19h0a9.374 9.374 0 0 1-12.062 8.982z");
}

:global(.k3cnofwci) {
  cx: 13.649px;
  cy: 24.079px;
  r: 5.942px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
