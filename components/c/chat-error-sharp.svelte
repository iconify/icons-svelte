<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac8ceco5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:chat-error-sharp" {...props}></Icon>
<style>
:global(.ac8ceco5w) {
  fill: currentColor;
  d: path("M3 20.077V3h18v14H6.077zm6.4-6.789l2.6-2.58l2.6 2.58l.688-.688l-2.58-2.6l2.58-2.6l-.688-.689L12 9.293l-2.6-2.58l-.689.688l2.581 2.6l-2.58 2.6z");
}

</style>
