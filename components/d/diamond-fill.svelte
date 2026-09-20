<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="b748gub2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:diamond-fill" {...props}></Icon>
<style>
:global(.b748gub2s) {
  fill: currentColor;
  d: path("M240 128a15.85 15.85 0 0 1-4.67 11.28l-96.05 96.06a16 16 0 0 1-22.56 0l-96-96.06a16 16 0 0 1 0-22.56l96.05-96.06a16 16 0 0 1 22.56 0l96.05 96.06A15.85 15.85 0 0 1 240 128");
}

</style>
