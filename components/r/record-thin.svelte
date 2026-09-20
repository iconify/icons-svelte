<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ylgwxnb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:record-thin" {...props}></Icon>
<style>
:global(.ylgwxnb5l) {
  fill: currentColor;
  d: path("M128 28a100 100 0 1 0 100 100A100.11 100.11 0 0 0 128 28m0 192a92 92 0 1 1 92-92a92.1 92.1 0 0 1-92 92m0-160a68 68 0 1 0 68 68a68.07 68.07 0 0 0-68-68m0 128a60 60 0 1 1 60-60a60.07 60.07 0 0 1-60 60");
}

</style>
