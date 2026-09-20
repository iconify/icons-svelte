<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u_317bb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:divider-short-16-filled" {...props}></Icon>
<style>
:global(.u_317bb_f) {
  fill: currentColor;
  d: path("M7.75 3a.75.75 0 0 1 .75.75v8.5a.75.75 0 0 1-1.5 0v-8.5A.75.75 0 0 1 7.75 3");
}

</style>
