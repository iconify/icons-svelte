<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvrfndvrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:dock-to-bottom-outline-sharp" {...props}></Icon>
<style>
:global(.rvrfndvrn) {
  fill: currentColor;
  d: path("M5 19h14v-3H5zm0-4h14V5H5zm0 1v3zm-1 4V4h16v16z");
}

</style>
