<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="l9mrmybba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:large-blue-diamond" {...props}></Icon>
<style>
:global(.l9mrmybba) {
  fill: currentColor;
  d: path("M2 32L32 2l29.999 30l-30 30z");
}

</style>
