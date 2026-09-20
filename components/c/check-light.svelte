<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dk7e0jxmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:check-light" {...props}></Icon>
<style>
:global(.dk7e0jxmq) {
  fill: currentColor;
  d: path("m228.24 76.24l-128 128a6 6 0 0 1-8.48 0l-56-56a6 6 0 0 1 8.48-8.48L96 191.51L219.76 67.76a6 6 0 0 1 8.48 8.48");
}

</style>
