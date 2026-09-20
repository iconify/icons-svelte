<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvzoi796h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:chevron-left-outline" {...props}></Icon>
<style>
:global(.bvzoi796h) {
  fill: currentColor;
  d: path("M14 17.308L8.692 12L14 6.692l.708.708l-4.6 4.6l4.6 4.6z");
}

</style>
