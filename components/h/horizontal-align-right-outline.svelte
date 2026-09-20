<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm9gs0bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:horizontal-align-right-outline" {...props}></Icon>
<style>
:global(.rm9gs0bpl) {
  fill: currentColor;
  d: path("M19 20V4h2v16zm-7-3l-1.4-1.4l2.6-2.6H3v-2h10.2l-2.6-2.6L12 7l5 5z");
}

</style>
