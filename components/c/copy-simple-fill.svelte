<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="obq7nxvaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:copy-simple-fill" {...props}></Icon>
<style>
:global(.obq7nxvaz) {
  fill: currentColor;
  d: path("M192 72v144a8 8 0 0 1-8 8H40a8 8 0 0 1-8-8V72a8 8 0 0 1 8-8h144a8 8 0 0 1 8 8m24-40H72a8 8 0 0 0 0 16h136v136a8 8 0 0 0 16 0V40a8 8 0 0 0-8-8");
}

</style>
