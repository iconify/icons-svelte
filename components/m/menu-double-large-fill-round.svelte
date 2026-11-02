<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2xtnil3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-double-large-fill-round" {...props}></Icon>
<style>
:global(.l2xtnil3l) {
  fill: currentColor;
  d: path("M21 8a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
