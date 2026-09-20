<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="g7vetjowq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-circle-up-28-filled" {...props}></Icon>
<style>
:global(.g7vetjowq) {
  fill: currentColor;
  d: path("M2 14c0 6.627 5.373 12 12 12s12-5.373 12-12S20.627 2 14 2S2 7.373 2 14m7.03 2.78a.75.75 0 0 1-1.06-1.06l5.5-5.5a.75.75 0 0 1 1.06 0l5.5 5.5a.75.75 0 1 1-1.06 1.06L14 11.81z");
}

</style>
