<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqa_97bdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bookmarks-sharp" {...props}></Icon>
<style>
:global(.rqa_97bdz) {
  fill: currentColor;
  d: path("M5 21V6.846h10.289V21l-5.145-2.654zm13-3.558V4H7.789V3H19v14.442z");
}

</style>
