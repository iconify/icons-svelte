<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fftkwizwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:plus-bold" {...props}></Icon>
<style>
:global(.fftkwizwx) {
  fill: currentColor;
  d: path("M228 128a12 12 0 0 1-12 12h-76v76a12 12 0 0 1-24 0v-76H40a12 12 0 0 1 0-24h76V40a12 12 0 0 1 24 0v76h76a12 12 0 0 1 12 12");
}

</style>
