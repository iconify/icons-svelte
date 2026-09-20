<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2osambjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-right-sharp" {...props}></Icon>
<style>
:global(.t2osambjn) {
  fill: currentColor;
  d: path("M10 17V7l5 5z");
}

</style>
