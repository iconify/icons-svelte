<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzsm6qbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-sort" {...props}></Icon>
<style>
:global(.yzsm6qbis) {
  fill: currentColor;
  d: path("M3 18h6v-2H3zM3 6v2h18V6zm0 7h12v-2H3z");
}

</style>
