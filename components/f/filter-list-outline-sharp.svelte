<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmvxeob3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:filter-list-outline-sharp" {...props}></Icon>
<style>
:global(.tmvxeob3y) {
  fill: currentColor;
  d: path("M10 18v-2h4v2zm-4-5v-2h12v2zM3 8V6h18v2z");
}

</style>
