<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n8m5ygbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:notebook-section-20-filled" {...props}></Icon>
<style>
:global(.n8m5ygbub) {
  fill: currentColor;
  d: path("M14 2.5a.5.5 0 0 0-1 0V3H8a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h5v.5a.5.5 0 0 0 1 0z");
}

</style>
