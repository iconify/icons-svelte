<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zl0ua_b9d"/><path class="e4futcbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fandango" {...props}></Icon>
<style>
:global(.e4futcbgm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 13.32l2.478 9.245a6.53 6.53 0 0 1 4.39 4.553a6.53 6.53 0 0 1-1.529 6.126l2.48 9.256l29.18-7.819l-2.536-9.469a6.53 6.53 0 0 1-4.33-4.329a6.53 6.53 0 0 1 1.585-5.914L34.68 5.5z");
}

:global(.zl0ua_b9d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.175 8.852l1.955 7.295l-8.337 2.234l1.954 7.295l8.338-2.234l1.955 7.295l-8.338 2.234l1.955 7.295");
}

</style>
