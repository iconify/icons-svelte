<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icijg0byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:description-outline-sharp" {...props}></Icon>
<style>
:global(.icijg0byg) {
  fill: currentColor;
  d: path("M8 18h8v-2H8zm0-4h8v-2H8zm-4 8V2h10l6 6v14zm9-13V4H6v16h12V9zM6 4v5zv16z");
}

</style>
