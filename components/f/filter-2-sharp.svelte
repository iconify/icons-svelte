<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv0d6ybtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:filter-2-sharp" {...props}></Icon>
<style>
:global(.dv0d6ybtl) {
  fill: currentColor;
  d: path("M11 15h6v-2h-4v-2h4V5h-6v2h4v2h-4zm-5 3V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
