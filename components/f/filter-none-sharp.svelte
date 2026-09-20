<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7lmgrhuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:filter-none-sharp" {...props}></Icon>
<style>
:global(.n7lmgrhuc) {
  fill: currentColor;
  d: path("M6 18V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
