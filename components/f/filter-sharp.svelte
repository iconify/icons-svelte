<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h334zx9nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:filter-sharp" {...props}></Icon>
<style>
:global(.h334zx9nt) {
  fill: currentColor;
  d: path("M9 14h10l-3.45-4.5l-2.3 3l-1.55-2zm-3 4V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
