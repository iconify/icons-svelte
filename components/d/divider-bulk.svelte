<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd18994yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:divider-bulk" {...props}></Icon>
<style>
:global(.gd18994yc) {
  fill: currentColor;
  d: path("M13 5v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0");
}

</style>
