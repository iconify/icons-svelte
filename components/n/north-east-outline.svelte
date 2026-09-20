<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sndm-x75k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:north-east-outline" {...props}></Icon>
<style>
:global(.sndm-x75k) {
  fill: currentColor;
  d: path("M5.708 19L5 18.292L16.292 7H9V6h9v9h-1V7.708z");
}

</style>
