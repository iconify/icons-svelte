<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q1qosxbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:fast-forward-16-filled" {...props}></Icon>
<style>
:global(.q1qosxbwd) {
  fill: currentColor;
  d: path("M8 4.465a1 1 0 0 1 1.576-.818l5.012 3.536a1 1 0 0 1 0 1.634l-5.012 3.536A1 1 0 0 1 8 11.536V9.232l-4.424 3.12A1 1 0 0 1 2 11.537V4.465a1 1 0 0 1 1.576-.818L8 6.768z");
}

</style>
