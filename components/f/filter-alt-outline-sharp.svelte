<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jii44-bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:filter-alt-outline-sharp" {...props}></Icon>
<style>
:global(.jii44-bis) {
  fill: currentColor;
  d: path("M11 19v-6.346L4.95 5h14.1L13 12.654V19zm1-6.7L16.95 6h-9.9zm0 0");
}

</style>
