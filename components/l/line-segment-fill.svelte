<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gaaqhvbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:line-segment-fill" {...props}></Icon>
<style>
:global(.gaaqhvbvj) {
  fill: currentColor;
  d: path("M211.81 83.79a28 28 0 0 1-33.12 4.83l-90.07 90.07a28 28 0 1 1-44.43-6.48a28 28 0 0 1 33.12-4.83l90.07-90.07a28 28 0 1 1 44.43 6.48");
}

</style>
