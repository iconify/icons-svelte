<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffblv3a4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bottom-drawer-outline-sharp" {...props}></Icon>
<style>
:global(.ffblv3a4h) {
  fill: currentColor;
  d: path("M3 21V3h18v18zM5 5v8.25L6.25 12h11.5L19 13.25V5zm0 14h14v-3l-2-2H7l-2 2zm0 0h14z");
}

</style>
