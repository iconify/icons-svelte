<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ws22iuovz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-arc-left-light" {...props}></Icon>
<style>
:global(.ws22iuovz) {
  fill: currentColor;
  d: path("M230 184a6 6 0 0 1-12 0a90 90 0 0 0-153.64-63.64L38.55 146H88a6 6 0 0 1 0 12H24a6 6 0 0 1-6-6V88a6 6 0 0 1 12 0v49.58l25.89-25.72A102 102 0 0 1 230 184");
}

</style>
