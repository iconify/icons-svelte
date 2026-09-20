<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc-t36tpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:content-copy-sharp" {...props}></Icon>
<style>
:global(.lc-t36tpr) {
  fill: currentColor;
  d: path("M7 18V2h13v16zm-4 4V6h2v14h11v2z");
}

</style>
