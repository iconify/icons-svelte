<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn7jahb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:amp-stories-outline" {...props}></Icon>
<style>
:global(.gn7jahb2u) {
  fill: currentColor;
  d: path("M7 20V4h10v16zm-4-2V6h2v12zm16 0V6h2v12zM9 18h6V6H9zm0 0V6z");
}

</style>
