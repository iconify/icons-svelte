<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="md8dn8b1e"/><path class="ixk09fb2q"/><path class="en95f2bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-flag-gabon" {...props}></Icon>
<style>
:global(.en95f2bez) {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("M0 14h36v8H0z");
}

:global(.ixk09fb2q) {
  fill: var(--svg-color--3a75c4, #3a75c4);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-5H0z");
}

:global(.md8dn8b1e) {
  fill: var(--svg-color--009e60, #009e60);
  d: path("M32 5H4a4 4 0 0 0-4 4v5h36V9a4 4 0 0 0-4-4");
}

</style>
