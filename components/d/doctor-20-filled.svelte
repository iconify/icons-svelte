<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sax-pq1oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:doctor-20-filled" {...props}></Icon>
<style>
:global(.sax-pq1oa) {
  fill: currentColor;
  d: path("M8.5 3A1.5 1.5 0 0 0 7 4.5v2.501H4.5a1.5 1.5 0 0 0-1.5 1.5v3a1.5 1.5 0 0 0 1.5 1.5H7v2.5a1.5 1.5 0 0 0 1.5 1.5h3a1.5 1.5 0 0 0 1.5-1.5v-2.5h2.5a1.5 1.5 0 0 0 1.5-1.5v-3a1.5 1.5 0 0 0-1.5-1.5H13V4.5A1.5 1.5 0 0 0 11.5 3z");
}

</style>
