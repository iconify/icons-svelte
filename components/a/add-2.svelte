<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8i9nwwrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:add-2" {...props}></Icon>
<style>
:global(.y8i9nwwrp) {
  fill: currentColor;
  d: path("M11 21v-8H3v-2h8V3h2v8h8v2h-8v8z");
}

</style>
