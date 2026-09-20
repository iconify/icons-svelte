<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n26j2r8gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:park-sharp" {...props}></Icon>
<style>
:global(.n26j2r8gq) {
  fill: currentColor;
  d: path("M13.95 22h-3.9v-4H3l4-6H5l7-10l7 10h-2l4 6h-7.05z");
}

</style>
