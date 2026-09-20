<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4l9feqgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:electric-bolt-sharp" {...props}></Icon>
<style>
:global(.j4l9feqgh) {
  fill: currentColor;
  d: path("m7 22l4-7.5l-8-1L15 2h2l-4 7.5l8 1L9 22z");
}

</style>
