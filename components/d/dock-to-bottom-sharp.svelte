<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3h7vebmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:dock-to-bottom-sharp" {...props}></Icon>
<style>
:global(.e3h7vebmw) {
  fill: currentColor;
  d: path("M5 14h14V5H5zm-2 7V3h18v18z");
}

</style>
