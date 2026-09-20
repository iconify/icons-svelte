<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iv4vb9gjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:document-footer-20-filled" {...props}></Icon>
<style>
:global(.iv4vb9gjh) {
  fill: currentColor;
  d: path("M6 2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm1 12h6a1 1 0 1 1 0 2H7a1 1 0 1 1 0-2");
}

</style>
