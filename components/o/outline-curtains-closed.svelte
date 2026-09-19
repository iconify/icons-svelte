<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhsacpclm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-curtains-closed" {...props}></Icon>
<style>
:global(.vhsacpclm) {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM13 5v14h-2V5zM6 5h3v14H6zm9 14V5h3v14z");
}

</style>
