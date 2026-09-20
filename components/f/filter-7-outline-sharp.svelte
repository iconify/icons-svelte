<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhdfrt82h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:filter-7-outline-sharp" {...props}></Icon>
<style>
:global(.rhdfrt82h) {
  fill: currentColor;
  d: path("M11 15h2l4-8V5h-6v2h4zm-5 3V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zm6-6V4z");
}

</style>
