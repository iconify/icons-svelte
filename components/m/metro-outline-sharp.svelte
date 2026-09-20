<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftukapb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:metro-outline-sharp" {...props}></Icon>
<style>
:global(.ftukapb8x) {
  fill: currentColor;
  d: path("M3 21V3h4.05L12 16.05L16.9 3H21v18h-3V8.75L13.275 21h-2.55L6 8.825V21z");
}

</style>
