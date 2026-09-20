<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qp1v5gbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:plus" {...props}></Icon>
<style>
:global(.qp1v5gbzb) {
  fill: currentColor;
  d: path("M224 128a8 8 0 0 1-8 8h-80v80a8 8 0 0 1-16 0v-80H40a8 8 0 0 1 0-16h80V40a8 8 0 0 1 16 0v80h80a8 8 0 0 1 8 8");
}

</style>
