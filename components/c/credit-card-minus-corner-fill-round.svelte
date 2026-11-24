<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4blvcbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-minus-corner-fill-round" {...props}></Icon>
<style>
:global(.u4blvcbgn) {
  fill: currentColor;
  d: path("M21.901 8H2.099A5.01 5.01 0 0 1 7 4h10a5.01 5.01 0 0 1 4.901 4M2 10h8v9a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5Zm19 5a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

</style>
