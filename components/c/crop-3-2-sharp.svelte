<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktop44b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-3-2-sharp" {...props}></Icon>
<style>
:global(.ktop44b7y) {
  fill: currentColor;
  d: path("M3 18V6h18v12z");
}

</style>
