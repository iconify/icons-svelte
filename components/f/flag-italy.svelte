<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="yb5z19bsg"/><path class="is9vgxh9p"/><path class="xpy8sjkzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-italy" {...props}></Icon>
<style>
:global(.is9vgxh9p) {
  fill: var(--svg-color--009246, #009246);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5z");
}

:global(.xpy8sjkzl) {
  fill: var(--svg-color--eee, #eee);
  d: path("M12 5h12v26H12z");
}

:global(.yb5z19bsg) {
  fill: var(--svg-color--ce2b37, #ce2b37);
  d: path("M36 27a4 4 0 0 1-4 4h-8V5h8a4 4 0 0 1 4 4z");
}

</style>
