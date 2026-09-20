<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ya9gmyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:border-all-outline" {...props}></Icon>
<style>
:global(.p-ya9gmyp) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm16-2v-6h-6v6zm0-14h-6v6h6zM5 5v6h6V5zm0 14h6v-6H5z");
}

</style>
