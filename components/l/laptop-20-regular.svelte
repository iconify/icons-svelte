<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qbsxyjxwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:laptop-20-regular" {...props}></Icon>
<style>
:global(.qbsxyjxwt) {
  fill: currentColor;
  d: path("M3 7a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2zm2-1a1 1 0 0 0-1 1v5a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1zm-3 9.5a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1-.5-.5");
}

</style>
