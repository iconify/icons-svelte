<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nw-w33bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:bench-20-filled" {...props}></Icon>
<style>
:global(.nw-w33bha) {
  fill: currentColor;
  d: path("M5 4a2 2 0 0 0-2 2v4h14V6a2 2 0 0 0-2-2zm-2.5 7a1.5 1.5 0 0 0 0 3H3v1.5a.5.5 0 0 0 1 0V14h12v1.5a.5.5 0 0 0 1 0V14h.5a1.5 1.5 0 0 0 0-3z");
}

</style>
