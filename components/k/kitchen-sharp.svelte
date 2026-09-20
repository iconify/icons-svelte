<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm-9o_b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:kitchen-sharp" {...props}></Icon>
<style>
:global(.zm-9o_b9j) {
  fill: currentColor;
  d: path("M8.192 8h1V5.385h-1zm0 8.116h1v-4.347h-1zM5 21V10.385h14V21zM5 9.385V3h14v6.385z");
}

</style>
