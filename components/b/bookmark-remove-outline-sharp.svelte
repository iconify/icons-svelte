<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk6z8l4hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bookmark-remove-outline-sharp" {...props}></Icon>
<style>
:global(.tk6z8l4hw) {
  fill: currentColor;
  d: path("M20 7h-5V6h5zm-8 9.917L6 19.5V4h7v1H7v12.95l5-2.15l5 2.15V11h1v8.5zM7 5h6z");
}

</style>
