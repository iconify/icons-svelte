<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t1pt2j9al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:bookmark-12-regular" {...props}></Icon>
<style>
:global(.t1pt2j9al) {
  fill: currentColor;
  d: path("M9 3a1 1 0 0 0-1-1H4a1 1 0 0 0-1 1v6.527l2.709-1.934a.5.5 0 0 1 .582 0L9 9.527zm1 7.5a.5.5 0 0 1-.791.407L6 8.614l-3.209 2.293A.5.5 0 0 1 2 10.5V3a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2z");
}

</style>
