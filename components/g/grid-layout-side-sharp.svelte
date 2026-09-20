<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="liby2ob4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:grid-layout-side-sharp" {...props}></Icon>
<style>
:global(.liby2ob4l) {
  fill: currentColor;
  d: path("M21 21V3zM3 21h10V3H3zm18 0V3h-6v18z");
}

</style>
