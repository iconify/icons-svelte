<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zmr-dy30i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:diamond-bold" {...props}></Icon>
<style>
:global(.zmr-dy30i) {
  fill: currentColor;
  d: path("M238.16 113.89L142.1 17.83a20 20 0 0 0-28.21 0l-96 96.06a20 20 0 0 0 0 28.22l96.05 96.06a20 20 0 0 0 28.21 0l96-96.06a20 20 0 0 0 0-28.22ZM128 218.33L37.68 128L128 37.67L218.32 128Z");
}

</style>
