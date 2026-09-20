<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="dkdneabma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-1-28-filled" {...props}></Icon>
<style>
:global(.dkdneabma) {
  fill: currentColor;
  d: path("M2 14a1 1 0 0 1 1-1h22a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1");
}

</style>
