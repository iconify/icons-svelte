<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcu0-pppt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-space-around-outline" {...props}></Icon>
<style>
:global(.jcu0-pppt) {
  fill: currentColor;
  d: path("M2 4V2h20v2zm0 18v-2h20v2zM7 9V6h10v3zm0 9v-3h10v3z");
}

</style>
