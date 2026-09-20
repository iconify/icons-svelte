<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_dgj4b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bottom-drawer-sharp" {...props}></Icon>
<style>
:global(.i_dgj4b5t) {
  fill: currentColor;
  d: path("M3 21V3h18v18zM5 5v8.25L6.25 12h11.5L19 13.25V5z");
}

</style>
