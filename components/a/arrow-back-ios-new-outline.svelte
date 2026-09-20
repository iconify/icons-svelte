<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqajplvwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-back-ios-new-outline" {...props}></Icon>
<style>
:global(.oqajplvwg) {
  fill: currentColor;
  d: path("M16 21.308L6.692 12L16 2.692l1.064 1.064L8.819 12l8.244 8.244z");
}

</style>
