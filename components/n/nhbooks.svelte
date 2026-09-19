<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qbhtstlzo"/><path class="q6o4o_4ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nhbooks" {...props}></Icon>
<style>
:global(.q6o4o_4ra) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 37.461V17.838l13 19.623V17.838");
}

:global(.qbhtstlzo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 8.5v31a4 4 0 0 0 4 4h23.2a4 4 0 0 0 4-4v-31a4 4 0 0 0-4-4h-.921v9.821l-3.887-3.91l-3.884 3.91V4.5H12.4a4 4 0 0 0-4 4");
}

</style>
