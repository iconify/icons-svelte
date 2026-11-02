<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtvf1bb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:more-grid-small-fill-sharp" {...props}></Icon>
<style>
:global(.xtvf1bb1t) {
  fill: currentColor;
  d: path("M7.158 8.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-6 6a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
