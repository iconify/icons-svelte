<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpfl_5hdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:list" {...props}></Icon>
<style>
:global(.kpfl_5hdl) {
  fill: currentColor;
  d: path("M3 13h2v-2H3zm0 4h2v-2H3zm0-8h2V7H3zm4 4h14v-2H7zm0 4h14v-2H7zM7 7v2h14V7z");
}

</style>
