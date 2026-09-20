<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8uvlibxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-start-arrow-notch-outline" {...props}></Icon>
<style>
:global(.y8uvlibxn) {
  fill: currentColor;
  d: path("M13 19L2 12l11-7l-3.425 6H22v2H9.575z");
}

</style>
