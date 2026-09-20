<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d45ndv4vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:page-footer-sharp" {...props}></Icon>
<style>
:global(.d45ndv4vp) {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-3.384V4h16v12.616z");
}

</style>
