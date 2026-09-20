<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="evg9qvbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:music-notes-simple-fill" {...props}></Icon>
<style>
:global(.evg9qvbis) {
  fill: currentColor;
  d: path("M212.92 17.69a8 8 0 0 0-6.86-1.45l-128 32A8 8 0 0 0 72 56v110.08A36 36 0 1 0 88 196V62.25l112-28v99.83A36 36 0 1 0 216 164V24a8 8 0 0 0-3.08-6.31");
}

</style>
