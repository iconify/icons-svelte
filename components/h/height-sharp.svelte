<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-8o9rvqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:height-sharp" {...props}></Icon>
<style>
:global(.l-8o9rvqz) {
  fill: currentColor;
  d: path("m11.98 20l-3.288-3.288l.689-.689l2.1 2.056V5.902L9.4 7.977l-.688-.688L12 4l3.289 3.289l-.708.713l-2.1-2.08v12.157l2.1-2.056l.688.689z");
}

</style>
