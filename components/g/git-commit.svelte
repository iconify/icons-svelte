<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ktekfvb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:git-commit" {...props}></Icon>
<style>
:global(.ktekfvb4h) {
  fill: currentColor;
  d: path("M248 120h-64.58a56 56 0 0 0-110.84 0H8a8 8 0 0 0 0 16h64.58a56 56 0 0 0 110.84 0H248a8 8 0 0 0 0-16m-120 48a40 40 0 1 1 40-40a40 40 0 0 1-40 40");
}

</style>
