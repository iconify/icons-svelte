<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnkwsrmbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:filter-alt-sharp" {...props}></Icon>
<style>
:global(.rnkwsrmbb) {
  fill: currentColor;
  d: path("M11 19v-6.346L4.95 5h14.1L13 12.654V19z");
}

</style>
