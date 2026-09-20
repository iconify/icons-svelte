<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uh2jajb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-bend-up-right-thin" {...props}></Icon>
<style>
:global(.uh2jajb8a) {
  fill: currentColor;
  d: path("m226.83 106.83l-48 48a4 4 0 0 1-5.66-5.66L214.34 108H128a92.1 92.1 0 0 0-92 92a4 4 0 0 1-8 0a100.11 100.11 0 0 1 100-100h86.34l-41.17-41.17a4 4 0 0 1 5.66-5.66l48 48a4 4 0 0 1 0 5.66");
}

</style>
