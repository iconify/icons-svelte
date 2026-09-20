<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="h47-4fpyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:minus-thin" {...props}></Icon>
<style>
:global(.h47-4fpyr) {
  fill: currentColor;
  d: path("M220 128a4 4 0 0 1-4 4H40a4 4 0 0 1 0-8h176a4 4 0 0 1 4 4");
}

</style>
