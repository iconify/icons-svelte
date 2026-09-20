<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vugy-hbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:note-add" {...props}></Icon>
<style>
:global(.vugy-hbte) {
  fill: currentColor;
  d: path("M11 18h2v-3h3v-2h-3v-3h-2v3H8v2h3zm-5 4q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v12q0 .825-.587 1.413T18 22zm7-13h5l-5-5z");
}

</style>
