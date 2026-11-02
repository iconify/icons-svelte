<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v64votbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:divide-fill-round" {...props}></Icon>
<style>
:global(.v64votbmg) {
  fill: currentColor;
  d: path("M12 6h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m6 5a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm-6 5h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
