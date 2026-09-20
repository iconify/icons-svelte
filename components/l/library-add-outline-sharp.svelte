<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzprtrnmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:library-add-outline-sharp" {...props}></Icon>
<style>
:global(.tzprtrnmn) {
  fill: currentColor;
  d: path("M13 14h2v-3h3V9h-3V6h-2v3h-3v2h3zm-7 4V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zM8 4v12z");
}

</style>
