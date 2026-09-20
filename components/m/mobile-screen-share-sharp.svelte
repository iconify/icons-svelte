<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4dt3kblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mobile-screen-share-sharp" {...props}></Icon>
<style>
:global(.c4dt3kblb) {
  fill: currentColor;
  d: path("M9 15v-4.5h4v-2l3 3l-3 3v-2h-2V15zm-4 8V1h14v22zm2-5h10V6H7z");
}

</style>
