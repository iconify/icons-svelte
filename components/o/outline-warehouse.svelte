<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbrzoebxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-warehouse" {...props}></Icon>
<style>
:global(.dbrzoebxj) {
  fill: currentColor;
  d: path("M20 8.35V19h-2v-8H6v8H4V8.35l8-3.2zM22 21V7L12 3L2 7v14h6v-8h8v8zm-11-2H9v2h2zm2-3h-2v2h2zm2 3h-2v2h2z");
}

</style>
