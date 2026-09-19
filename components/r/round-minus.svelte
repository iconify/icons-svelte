<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_lwkacpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-minus" {...props}></Icon>
<style>
:global(.r_lwkacpr) {
  fill: currentColor;
  d: path("M18 12.998H6a1 1 0 0 1 0-2h12a1 1 0 0 1 0 2");
}

</style>
