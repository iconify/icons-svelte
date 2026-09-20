<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s__g6yt1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:border-outer-outline-sharp" {...props}></Icon>
<style>
:global(.s__g6yt1x) {
  fill: currentColor;
  d: path("M5 19h14V5H5zm-2 2V3h18v18zm4-8v-2h2v2zm4 4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm4 4v-2h2v2z");
}

</style>
