<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sywzcubld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:filter-24-filled" {...props}></Icon>
<style>
:global(.sywzcubld) {
  fill: currentColor;
  d: path("M10 16h4a1 1 0 0 1 .117 1.993L14 18h-4a1 1 0 0 1-.117-1.993zh4zm-2-5h8a1 1 0 0 1 .117 1.993L16 13H8a1 1 0 0 1-.117-1.993zh8zM5 6h14a1 1 0 0 1 .117 1.993L19 8H5a1 1 0 0 1-.117-1.993zh14z");
}

</style>
