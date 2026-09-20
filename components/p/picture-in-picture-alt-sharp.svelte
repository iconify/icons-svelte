<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icija0bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:picture-in-picture-alt-sharp" {...props}></Icon>
<style>
:global(.icija0bln) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm9-3h8v-6h-8zm4-3");
}

</style>
