<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tm_wncc5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-double-up-20-filled" {...props}></Icon>
<style>
:global(.tm_wncc5w) {
  fill: currentColor;
  d: path("M9.47 9.22a.75.75 0 0 1 1.06 0l5.25 5.25a.75.75 0 0 1-1.06 1.06L10 10.81l-4.72 4.72a.75.75 0 0 1-1.06-1.06zm0-5.5a.75.75 0 0 1 1.06 0l5.25 5.25a.75.75 0 0 1-1.06 1.06L10 5.31l-4.72 4.72a.75.75 0 0 1-1.06-1.06z");
}

</style>
