<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf43jb_jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:dock-to-left-sharp" {...props}></Icon>
<style>
:global(.qf43jb_jq) {
  fill: currentColor;
  d: path("M5 19h9V5H5zm-2 2V3h18v18z");
}

</style>
