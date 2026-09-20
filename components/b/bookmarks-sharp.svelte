<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdavhzbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bookmarks-sharp" {...props}></Icon>
<style>
:global(.sdavhzbyv) {
  fill: currentColor;
  d: path("M4 22V6h12v16l-6-3zm14-4V4H7V2h13v16z");
}

</style>
