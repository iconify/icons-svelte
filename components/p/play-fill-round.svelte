<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caz71cbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:play-fill-round" {...props}></Icon>
<style>
:global(.caz71cbkh) {
  fill: currentColor;
  d: path("M19.12 8.608a4 4 0 0 1 0 6.784l-8 5A4.001 4.001 0 0 1 5 17V7a4 4 0 0 1 6.12-3.392Z");
}

</style>
