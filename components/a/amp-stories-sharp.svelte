<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scghyeb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:amp-stories-sharp" {...props}></Icon>
<style>
:global(.scghyeb3q) {
  fill: currentColor;
  d: path("M7 20V4h10v16zm-4-2V6h2v12zm16 0V6h2v12z");
}

</style>
