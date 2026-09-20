<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwdcovb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:page-footer-outline-sharp" {...props}></Icon>
<style>
:global(.xwdcovb8d) {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-3.384V4h16v12.616zm1-1h14V5H5zm0 0V5z");
}

</style>
