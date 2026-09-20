<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf6fnmbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:book-sharp" {...props}></Icon>
<style>
:global(.qf6fnmbaw) {
  fill: currentColor;
  d: path("M4 22V2h16v20zm7-11l2.5-1.5L16 11V4h-5z");
}

</style>
