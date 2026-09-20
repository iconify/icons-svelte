<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho4oa_b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-italic-sharp" {...props}></Icon>
<style>
:global(.ho4oa_b5z) {
  fill: currentColor;
  d: path("M5 19v-2.5h4l3-9H8V5h10v2.5h-3.5l-3 9H15V19z");
}

</style>
