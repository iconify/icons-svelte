<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a2hiikbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-reply-16-filled" {...props}></Icon>
<style>
:global(.a2hiikbjl) {
  fill: currentColor;
  d: path("M6.78 4.28a.75.75 0 0 0-1.06-1.06l-3.5 3.5a.75.75 0 0 0 0 1.06l3.5 3.5a.75.75 0 0 0 1.06-1.06L4.56 8h3.69a4.25 4.25 0 0 1 4.25 4.25a.75.75 0 0 0 1.5 0A5.75 5.75 0 0 0 8.25 6.5H4.56z");
}

</style>
