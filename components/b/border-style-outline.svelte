<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu0p-pbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:border-style-outline" {...props}></Icon>
<style>
:global(.bu0p-pbmo) {
  fill: currentColor;
  d: path("M7 21v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zM3 21V3h18v2H5v16z");
}

</style>
