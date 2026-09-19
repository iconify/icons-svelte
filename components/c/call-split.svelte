<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ditn3_bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:call-split" {...props}></Icon>
<style>
:global(.ditn3_bwt) {
  fill: currentColor;
  d: path("m14 4l2.29 2.29l-2.88 2.88l1.42 1.42l2.88-2.88L20 10V4zm-4 0H4v6l2.29-2.29l4.71 4.7V20h2v-8.41l-5.29-5.3z");
}

</style>
