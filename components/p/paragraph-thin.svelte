<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bv7m226wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:paragraph-thin" {...props}></Icon>
<style>
:global(.bv7m226wz) {
  fill: currentColor;
  d: path("M208 44H96a60 60 0 0 0 0 120h44v44a4 4 0 0 0 8 0V52h32v156a4 4 0 0 0 8 0V52h20a4 4 0 0 0 0-8m-68 112H96a52 52 0 0 1 0-104h44Z");
}

</style>
