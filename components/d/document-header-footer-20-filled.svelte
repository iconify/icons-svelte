<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wyvm6-wgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:document-header-footer-20-filled" {...props}></Icon>
<style>
:global(.wyvm6-wgp) {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2zm2 1a1 1 0 0 0 1 1h6a1 1 0 1 0 0-2H7a1 1 0 0 0-1 1m0 10a1 1 0 0 0 1 1h6a1 1 0 1 0 0-2H7a1 1 0 0 0-1 1");
}

</style>
