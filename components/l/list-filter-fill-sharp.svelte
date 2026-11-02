<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m538sebkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-filter-fill-sharp" {...props}></Icon>
<style>
:global(.m538sebkk) {
  fill: currentColor;
  d: path("M4 5h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m3 6h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m3 6h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

</style>
