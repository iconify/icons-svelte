<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1do82chx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:dock-to-bottom-sharp" {...props}></Icon>
<style>
:global(.i1do82chx) {
  fill: currentColor;
  d: path("M5 15h14V5H5zm-1 5V4h16v16z");
}

</style>
