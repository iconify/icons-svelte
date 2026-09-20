<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zlte7gb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:moon-fill" {...props}></Icon>
<style>
:global(.zlte7gb_s) {
  fill: currentColor;
  d: path("M235.54 150.21a104.84 104.84 0 0 1-37 52.91A104 104 0 0 1 32 120a103.1 103.1 0 0 1 20.88-62.52a104.84 104.84 0 0 1 52.91-37a8 8 0 0 1 10 10a88.08 88.08 0 0 0 109.8 109.8a8 8 0 0 1 10 10Z");
}

</style>
