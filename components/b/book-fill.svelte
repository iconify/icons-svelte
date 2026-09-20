<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ye2fv57zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:book-fill" {...props}></Icon>
<style>
:global(.ye2fv57zm) {
  fill: currentColor;
  d: path("M216 32v160a8 8 0 0 1-8 8H72a16 16 0 0 0-16 16h136a8 8 0 0 1 0 16H48a8 8 0 0 1-8-8V56a32 32 0 0 1 32-32h136a8 8 0 0 1 8 8");
}

</style>
