<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_-_6xbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:perm-media-sharp" {...props}></Icon>
<style>
:global(.g_-_6xbqe) {
  fill: currentColor;
  d: path("M1 21V6h2v13h17v2zm4-4V2h7l2 2h9v13zm4-4h10l-3.45-4.5l-2.3 3l-1.55-2z");
}

</style>
