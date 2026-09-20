<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsqzvdndj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:library-add-sharp" {...props}></Icon>
<style>
:global(.lsqzvdndj) {
  fill: currentColor;
  d: path("M13 14h2v-3h3V9h-3V6h-2v3h-3v2h3zm-7 4V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
