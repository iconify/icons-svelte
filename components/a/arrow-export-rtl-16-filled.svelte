<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h9oglsbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-export-rtl-16-filled" {...props}></Icon>
<style>
:global(.h9oglsbdu) {
  fill: currentColor;
  d: path("M14.25 3a.75.75 0 0 0-.75.75v8.5a.75.75 0 0 0 1.5 0v-8.5a.75.75 0 0 0-.75-.75m-8.47.72a.75.75 0 0 0-1.06 0l-3.5 3.5a.75.75 0 0 0 0 1.06l3.5 3.5a.75.75 0 0 0 1.06-1.06L3.56 8.5h7.69a.75.75 0 0 0 0-1.5H3.56l2.22-2.22a.75.75 0 0 0 0-1.06");
}

</style>
