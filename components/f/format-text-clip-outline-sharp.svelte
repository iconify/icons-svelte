<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhievvbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-text-clip-outline-sharp" {...props}></Icon>
<style>
:global(.lhievvbft) {
  fill: currentColor;
  d: path("M4 20V4h2v16zm14 0v-7H8v-2h10V4h2v16z");
}

</style>
