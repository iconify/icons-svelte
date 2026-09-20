<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu62vsfal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-3-2-outline-sharp" {...props}></Icon>
<style>
:global(.zu62vsfal) {
  fill: currentColor;
  d: path("M3 18V6h18v12zm2-2h14V8H5zm0 0V8z");
}

</style>
