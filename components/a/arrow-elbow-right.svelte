<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i7b6zh-8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-elbow-right" {...props}></Icon>
<style>
:global(.i7b6zh-8v) {
  fill: currentColor;
  d: path("M240 80v72a8 8 0 0 1-16 0V99.31l-98.34 98.35a8 8 0 0 1-11.32 0l-96-96a8 8 0 0 1 11.32-11.32L120 180.69L212.69 88H160a8 8 0 0 1 0-16h72a8 8 0 0 1 8 8");
}

</style>
