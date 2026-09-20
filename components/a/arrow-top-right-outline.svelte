<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpgddmbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-top-right-outline" {...props}></Icon>
<style>
:global(.vpgddmbfx) {
  fill: currentColor;
  d: path("M5 20V8h11.175l-3.6-3.575L14 3l6 6l-6.025 6.025l-1.4-1.425l3.6-3.6H7v10z");
}

</style>
