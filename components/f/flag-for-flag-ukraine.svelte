<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="avxj11blr"/><path class="v2oqoeb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-flag-ukraine" {...props}></Icon>
<style>
:global(.avxj11blr) {
  fill: var(--svg-color--005bbb, #005bbb);
  d: path("M32 5H4a4 4 0 0 0-4 4v9h36V9a4 4 0 0 0-4-4");
}

:global(.v2oqoeb3w) {
  fill: var(--svg-color--ffd500, #ffd500);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4v-9h36z");
}

</style>
