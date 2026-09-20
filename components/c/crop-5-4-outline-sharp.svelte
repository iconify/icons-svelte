<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uymqj-bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-5-4-outline-sharp" {...props}></Icon>
<style>
:global(.uymqj-bpz) {
  fill: currentColor;
  d: path("M3 20V4h18v16zm2-2h14V6H5zm0 0V6z");
}

</style>
