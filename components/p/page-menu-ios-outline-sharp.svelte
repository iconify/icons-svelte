<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arir_fbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:page-menu-ios-outline-sharp" {...props}></Icon>
<style>
:global(.arir_fbwn) {
  fill: currentColor;
  d: path("M4 20v-1h10.366v1zm0-3.384v-1h16v1zm0-3.385V4h16v9.23zm1-1h14V5H5zm0 0V5z");
}

</style>
