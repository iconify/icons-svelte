<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7n1b4iis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:reorder-outline-sharp" {...props}></Icon>
<style>
:global(.c7n1b4iis) {
  fill: currentColor;
  d: path("M3 19v-2h18v2zm0-4v-2h18v2zm0-4V9h18v2zm0-4V5h18v2z");
}

</style>
