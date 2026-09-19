<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3gkltbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-height" {...props}></Icon>
<style>
:global(.d3gkltbvj) {
  fill: currentColor;
  d: path("M13 6.99h3L12 3L8 6.99h3v10.02H8L12 21l4-3.99h-3z");
}

</style>
