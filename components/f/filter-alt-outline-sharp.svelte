<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhvbb4bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:filter-alt-outline-sharp" {...props}></Icon>
<style>
:global(.mhvbb4bsi) {
  fill: currentColor;
  d: path("M10 20v-7L2.95 4h18.1L14 13v7zm2-7.7L16.95 6h-9.9zm0 0");
}

</style>
