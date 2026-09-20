<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubmnd0bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:dock-to-left-sharp" {...props}></Icon>
<style>
:global(.ubmnd0bhf) {
  fill: currentColor;
  d: path("M5 19h10V5H5zm-1 1V4h16v16z");
}

</style>
