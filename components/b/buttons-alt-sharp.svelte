<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oayo3wp4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:buttons-alt-sharp" {...props}></Icon>
<style>
:global(.oayo3wp4s) {
  fill: currentColor;
  d: path("M2 18V6h20v12zm5.25-3h1.5v-2.25H11v-1.5H8.75V9h-1.5v2.25H5v1.5h2.25z");
}

</style>
