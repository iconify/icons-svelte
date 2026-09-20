<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hfxto-nig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:molecule-20-regular" {...props}></Icon>
<style>
:global(.hfxto-nig) {
  fill: currentColor;
  d: path("M13 10a4 4 0 1 0-3.774-2.672l-2.121 1.06a3.5 3.5 0 1 0 1.291 5.077l2.69 1.384A2.503 2.503 0 0 0 13.5 18a2.5 2.5 0 1 0-1.966-4.045l-2.7-1.388a3.5 3.5 0 0 0-.828-3.511l1.668-.834A4 4 0 0 0 13 10m0-1a3 3 0 1 1 0-6a3 3 0 0 1 0 6m-7.5 5a2.5 2.5 0 1 1 0-5a2.5 2.5 0 0 1 0 5m9.5 1.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
