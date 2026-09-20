<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln9on4c1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:post" {...props}></Icon>
<style>
:global(.ln9on4c1z) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1.77-6.038h12.46v-1.116H5.77zm0 2.692h12.46v-.885H5.77z");
}

</style>
