<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="g49k_4bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:minus" {...props}></Icon>
<style>
:global(.g49k_4bmx) {
  fill: currentColor;
  d: path("M224 128a8 8 0 0 1-8 8H40a8 8 0 0 1 0-16h176a8 8 0 0 1 8 8");
}

</style>
