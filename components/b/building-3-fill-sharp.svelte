<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oio_i1biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-3-fill-sharp" {...props}></Icon>
<style>
:global(.oio_i1biu) {
  fill: currentColor;
  d: path("M6 4a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v15h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1v-6a1 1 0 0 1 .375-.781L6 10.919Zm3.375 4.219a1 1 0 0 1 1.25 0l5 4A1 1 0 0 1 16 13v6h2V5H8v4.319Z");
}

</style>
