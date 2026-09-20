<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zy1yti3jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:paragraph-light" {...props}></Icon>
<style>
:global(.zy1yti3jf) {
  fill: currentColor;
  d: path("M208 42H96a62 62 0 0 0 0 124h42v42a6 6 0 0 0 12 0V54h28v154a6 6 0 0 0 12 0V54h18a6 6 0 0 0 0-12m-70 112H96a50 50 0 0 1 0-100h42Z");
}

</style>
