<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aexnd4hgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:move-selection-down" {...props}></Icon>
<style>
:global(.aexnd4hgf) {
  fill: currentColor;
  d: path("M6 22V10h12v12zM6 8V6h2v2zm10 0V6h2v2zM6 4V2h2v2zm5 0V2h2v2zm5 0V2h2v2z");
}

</style>
