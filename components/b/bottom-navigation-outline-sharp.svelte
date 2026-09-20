<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0hgc4bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bottom-navigation-outline-sharp" {...props}></Icon>
<style>
:global(.r0hgc4bkr) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-6h14V5H5zm0 2v2h14v-2zm0 0v2z");
}

</style>
