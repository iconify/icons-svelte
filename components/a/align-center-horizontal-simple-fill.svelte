<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="en960lp3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:align-center-horizontal-simple-fill" {...props}></Icon>
<style>
:global(.en960lp3z) {
  fill: currentColor;
  d: path("M224 96v64a16 16 0 0 1-16 16h-72v32a8 8 0 0 1-16 0v-32H48a16 16 0 0 1-16-16V96a16 16 0 0 1 16-16h72V48a8 8 0 0 1 16 0v32h72a16 16 0 0 1 16 16");
}

</style>
