<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btf4m5b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:move-item-outline-sharp" {...props}></Icon>
<style>
:global(.btf4m5b2w) {
  fill: currentColor;
  d: path("M20.15 13H8v-2h12.15L18.6 9.45L20 8l4 4l-4 4l-1.4-1.45zM15 9V5H5v14h10v-4h2v6H3V3h14v6z");
}

</style>
