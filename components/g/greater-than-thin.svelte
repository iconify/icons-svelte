<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="yck7wgd5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:greater-than-thin" {...props}></Icon>
<style>
:global(.yck7wgd5o) {
  fill: currentColor;
  d: path("M220 128a4 4 0 0 1-2.29 3.62l-152 72A3.85 3.85 0 0 1 64 204a4 4 0 0 1-1.71-7.62L206.66 128L62.29 59.62a4 4 0 0 1 3.42-7.23l152 72A4 4 0 0 1 220 128");
}

</style>
