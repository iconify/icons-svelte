<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx4an3bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circuit-board-fill-sharp" {...props}></Icon>
<style>
:global(.qx4an3bse) {
  fill: currentColor;
  d: path("M16 2v6h-4.171a3 3 0 1 0 0 2H17a1 1 0 0 0 1-1V2h3a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H8v-6h4.171a3 3 0 1 0 0-2H7a1 1 0 0 0-1 1v7H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Z");
}

</style>
