<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sgk9lzb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-flow-diagonal-up-right-20-filled" {...props}></Icon>
<style>
:global(.sgk9lzb8s) {
  fill: currentColor;
  d: path("M10.5 4a.5.5 0 0 0 0 1h3.793l-6.555 6.555a3 3 0 1 0 .707.707L15 5.708V9.5a.5.5 0 0 0 1 0v-5a.5.5 0 0 0-.5-.5z");
}

</style>
