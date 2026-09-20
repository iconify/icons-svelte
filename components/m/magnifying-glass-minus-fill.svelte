<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ger3qfbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:magnifying-glass-minus-fill" {...props}></Icon>
<style>
:global(.ger3qfbnk) {
  fill: currentColor;
  d: path("m229.66 218.34l-50.06-50.06a88.21 88.21 0 1 0-11.32 11.31l50.06 50.07a8 8 0 0 0 11.32-11.32M144 120H80a8 8 0 0 1 0-16h64a8 8 0 0 1 0 16");
}

</style>
