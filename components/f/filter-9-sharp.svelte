<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_s8w1dgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:filter-9-sharp" {...props}></Icon>
<style>
:global(.r_s8w1dgy) {
  fill: currentColor;
  d: path("M12 15h5V5h-6v6h4v2h-3zm3-6h-2V7h2zm-9 9V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
