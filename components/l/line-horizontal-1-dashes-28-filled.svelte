<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="kaktcxb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-1-dashes-28-filled" {...props}></Icon>
<style>
:global(.kaktcxb1f) {
  fill: currentColor;
  d: path("M2 14a1 1 0 0 1 1-1h4a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m9 0a1 1 0 0 1 1-1h4a1 1 0 1 1 0 2h-4a1 1 0 0 1-1-1m9 0a1 1 0 0 1 1-1h4a1 1 0 1 1 0 2h-4a1 1 0 0 1-1-1");
}

</style>
