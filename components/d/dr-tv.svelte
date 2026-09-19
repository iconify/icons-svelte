<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zc7hhleka"/><path class="p8aty-yxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dr-tv" {...props}></Icon>
<style>
:global(.p8aty-yxu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34 24l-16-9.238v18.476z");
}

:global(.zc7hhleka) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.797 8.797c8.397-8.396 22.01-8.396 30.406 0s8.396 22.01 0 30.406s-22.01 8.396-30.406 0");
}

</style>
