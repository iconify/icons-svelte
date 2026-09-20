<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwbfslbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-space-even-outline" {...props}></Icon>
<style>
:global(.nwbfslbdt) {
  fill: currentColor;
  d: path("M3 4V3h18v1zm0 17v-1h18v1zM7.5 9.5v-2h9v2zm0 7v-2h9v2z");
}

</style>
