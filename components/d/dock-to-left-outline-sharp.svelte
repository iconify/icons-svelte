<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqwjjtbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:dock-to-left-outline-sharp" {...props}></Icon>
<style>
:global(.fqwjjtbma) {
  fill: currentColor;
  d: path("M16 19h3V5h-3zM5 19h9V5H5zm11 0h3zM3 21V3h18v18z");
}

</style>
