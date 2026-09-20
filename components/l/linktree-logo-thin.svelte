<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="h_1rrwojy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:linktree-logo-thin" {...props}></Icon>
<style>
:global(.h_1rrwojy) {
  fill: currentColor;
  d: path("M132 160v72a4 4 0 0 1-8 0v-72a4 4 0 0 1 8 0m76-60h-70.34l49.17-49.17a4 4 0 1 0-5.66-5.66L132 94.34V24a4 4 0 0 0-8 0v70.34L74.83 45.17a4 4 0 0 0-5.66 5.66L118.34 100H48a4 4 0 0 0 0 8h70.34l-49.17 49.17a4 4 0 0 0 5.66 5.66L128 109.66l53.17 53.17a4 4 0 0 0 5.66-5.66L137.66 108H208a4 4 0 0 0 0-8");
}

</style>
