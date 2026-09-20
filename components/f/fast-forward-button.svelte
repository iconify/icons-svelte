<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rykn6etxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:fast-forward-button" {...props}></Icon>
<style>
:global(.rykn6etxo) {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("m6.24 98.99l54.93-31.71v31.71L121.76 64L61.17 29.01v31.72L6.24 29.01z");
}

</style>
