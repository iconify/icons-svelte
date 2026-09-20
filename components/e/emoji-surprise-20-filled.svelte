<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ayz78bboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:emoji-surprise-20-filled" {...props}></Icon>
<style>
:global(.ayz78bboa) {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m5.5-.5a1 1 0 1 0 0-2a1 1 0 0 0 0 2m4.25 3a1.75 1.75 0 1 0-3.5 0a1.75 1.75 0 0 0 3.5 0m.75-3a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
