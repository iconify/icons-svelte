<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cikm25usp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:camera-indoor-sharp" {...props}></Icon>
<style>
:global(.cikm25usp) {
  fill: currentColor;
  d: path("M4 21V9l8-6l8 6v12zm4-4h6v-2l2 1.05v-4.1L14 13v-2H8z");
}

</style>
