<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fmay49bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:chat-teardrop-text-fill" {...props}></Icon>
<style>
:global(.fmay49bhn) {
  fill: currentColor;
  d: path("M132 24A100.11 100.11 0 0 0 32 124v84a16 16 0 0 0 16 16h84a100 100 0 0 0 0-200m32 128H96a8 8 0 0 1 0-16h68a8 8 0 0 1 0 16m0-32H96a8 8 0 0 1 0-16h68a8 8 0 0 1 0 16");
}

</style>
