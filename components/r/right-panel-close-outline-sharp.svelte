<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq93tactv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:right-panel-close-outline-sharp" {...props}></Icon>
<style>
:global(.jq93tactv) {
  fill: currentColor;
  d: path("M8.404 15.173L11.596 12L8.404 8.827zM16 19h3V5h-3zM5 19h10V5H5zm11 0h3zM4 20V4h16v16z");
}

</style>
