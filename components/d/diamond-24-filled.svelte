<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2te9mben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:diamond-24-filled" {...props}></Icon>
<style>
:global(.p2te9mben) {
  fill: currentColor;
  d: path("M9.713 1.962a3.25 3.25 0 0 1 4.596 0l7.75 7.75a3.25 3.25 0 0 1 0 4.597l-7.75 7.75a3.25 3.25 0 0 1-4.596 0l-7.75-7.75a3.25 3.25 0 0 1 0-4.597z");
}

</style>
