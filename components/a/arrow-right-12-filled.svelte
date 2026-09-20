<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="llwxbbbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-right-12-filled" {...props}></Icon>
<style>
:global(.llwxbbbjj) {
  fill: currentColor;
  d: path("M1.5 6a.75.75 0 0 1 .75-.75h5.94L6.22 3.28a.75.75 0 0 1 1.06-1.06l3.25 3.25a.75.75 0 0 1 0 1.06L7.28 9.78a.75.75 0 0 1-1.06-1.06l1.97-1.97H2.25A.75.75 0 0 1 1.5 6");
}

</style>
