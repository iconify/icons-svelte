<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4a4eob2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:dropdown-sharp" {...props}></Icon>
<style>
:global(.u4a4eob2r) {
  fill: currentColor;
  d: path("M12 12h6V6h-6zm-8 8V4h16v16z");
}

</style>
