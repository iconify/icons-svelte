<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9gdoubtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:inventory-2-outline-sharp" {...props}></Icon>
<style>
:global(.j9gdoubtb) {
  fill: currentColor;
  d: path("M3 22V9H2V2h20v7h-1v13zm2-2h14V9H5zM4 7h16V4H4zm5 7h6v-2H9zm3 .5");
}

</style>
