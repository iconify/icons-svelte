<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra_odxw9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:picture-in-picture-large-sharp" {...props}></Icon>
<style>
:global(.ra_odxw9j) {
  fill: currentColor;
  d: path("M6 16V6h12v10zm-4 4v-2h18V4h2v16z");
}

</style>
