<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nyhiu2wqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:bowling-ball" {...props}></Icon>
<style>
:global(.nyhiu2wqu) {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m0 192a88 88 0 1 1 88-88a88.1 88.1 0 0 1-88 88m16-100a12 12 0 1 1-12-12a12 12 0 0 1 12 12m20-12a12 12 0 1 1 12-12a12 12 0 0 1-12 12m20 28a12 12 0 1 1-12-12a12 12 0 0 1 12 12");
}

</style>
