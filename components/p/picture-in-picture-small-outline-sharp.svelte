<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epygqxank"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:picture-in-picture-small-outline-sharp" {...props}></Icon>
<style>
:global(.epygqxank) {
  fill: currentColor;
  d: path("M3 19v-1h17V5h1v14zm6.923-3.384V9.923h7.693v5.693z");
}

</style>
