<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty-lzqbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:open-in-new-down-sharp" {...props}></Icon>
<style>
:global(.ty-lzqbvr) {
  fill: currentColor;
  d: path("M4 20V4h16v7.616h-1V5H5v14h6.616v1zm10 0v-1h4.312L9.089 9.777l.688-.688L19 18.287V14h1v6z");
}

</style>
