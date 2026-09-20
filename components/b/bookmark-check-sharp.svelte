<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpa8r9-vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bookmark-check-sharp" {...props}></Icon>
<style>
:global(.xpa8r9-vw) {
  fill: currentColor;
  d: path("m10.95 14l4.95-4.95l-1.425-1.4l-3.525 3.525L9.525 9.75L8.1 11.175zM5 21V3h14v18l-7-3z");
}

</style>
