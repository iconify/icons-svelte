<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y6qh_7b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:glyph-notifications" {...props}></Icon>
<style>
:global(.y6qh_7b3q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4M13 35l22-22");
}

</style>
