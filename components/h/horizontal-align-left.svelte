<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a28bgccdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:horizontal-align-left" {...props}></Icon>
<style>
:global(.a28bgccdc) {
  fill: currentColor;
  d: path("M4 19V5h1v14zm8-2.692L7.692 12L12 7.692l.708.708l-3.1 3.1H20v1H9.608l3.1 3.1z");
}

</style>
