<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="u7fh7yzxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:caret-double-left" {...props}></Icon>
<style>
:global(.u7fh7yzxk) {
  fill: currentColor;
  d: path("M205.66 202.34a8 8 0 0 1-11.32 11.32l-80-80a8 8 0 0 1 0-11.32l80-80a8 8 0 0 1 11.32 11.32L131.31 128ZM51.31 128l74.35-74.34a8 8 0 0 0-11.32-11.32l-80 80a8 8 0 0 0 0 11.32l80 80a8 8 0 0 0 11.32-11.32Z");
}

</style>
