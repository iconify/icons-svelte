<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="yxgle5bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:rectangles-two-fill" {...props}></Icon>
<style>
:global(.yxgle5bip) {
  fill: currentColor;
  d: path("M224 152v40a16 16 0 0 1-16 16H48a16 16 0 0 1-16-16v-40a16 16 0 0 1 16-16h160a16 16 0 0 1 16 16M208 48H48a16 16 0 0 0-16 16v40a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V64a16 16 0 0 0-16-16");
}

</style>
