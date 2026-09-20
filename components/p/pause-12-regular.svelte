<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h1ch7mbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:pause-12-regular" {...props}></Icon>
<style>
:global(.h1ch7mbeb) {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1zm1 0v6h1V3zm4 0a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1zm1 0v6h1V3z");
}

</style>
