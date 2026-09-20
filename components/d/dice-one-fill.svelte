<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x2_q8xp6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:dice-one-fill" {...props}></Icon>
<style>
:global(.x2_q8xp6r) {
  fill: currentColor;
  d: path("M192 32H64a32 32 0 0 0-32 32v128a32 32 0 0 0 32 32h128a32 32 0 0 0 32-32V64a32 32 0 0 0-32-32m-64 108a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
