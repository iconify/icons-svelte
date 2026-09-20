<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya2--l60b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:ad-outline-sharp" {...props}></Icon>
<style>
:global(.ya2--l60b) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V8H5z");
}

</style>
