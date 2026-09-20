<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="epla4-ziz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:paragraph-bold" {...props}></Icon>
<style>
:global(.epla4-ziz) {
  fill: currentColor;
  d: path("M208 36H96a68 68 0 0 0 0 136h36v36a12 12 0 0 0 24 0V60h16v148a12 12 0 0 0 24 0V60h12a12 12 0 0 0 0-24m-76 112H96a44 44 0 0 1 0-88h36Z");
}

</style>
