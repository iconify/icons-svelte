<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="r95f96rcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:heavy-plus-sign" {...props}></Icon>
<style>
:global(.r95f96rcc) {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M31 15H21V5a3 3 0 1 0-6 0v10H5a3 3 0 1 0 0 6h10v10a3 3 0 1 0 6 0V21h10a3 3 0 1 0 0-6");
}

</style>
