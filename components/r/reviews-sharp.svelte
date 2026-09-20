<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alklbdcdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:reviews-sharp" {...props}></Icon>
<style>
:global(.alklbdcdh) {
  fill: currentColor;
  d: path("M3 20.077V3h18v14H6.077zm6.517-6.404L12 12.167l2.483 1.506l-.66-2.825l2.196-1.884l-2.886-.256L12 6.058l-1.133 2.65l-2.886.256l2.196 1.884z");
}

</style>
