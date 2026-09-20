<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhi530bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-down-right-24-filled" {...props}></Icon>
<style>
:global(.mhi530bdw) {
  fill: currentColor;
  d: path("M18 7.208c0-1.114-1.346-1.672-2.133-.884l-9.543 9.543c-.788.787-.23 2.133.884 2.133h9.042A1.75 1.75 0 0 0 18 16.25z");
}

</style>
