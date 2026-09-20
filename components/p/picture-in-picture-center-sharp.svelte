<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnl2zib4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:picture-in-picture-center-sharp" {...props}></Icon>
<style>
:global(.mnl2zib4p) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm5.154-4.154h7.692V9.154H8.154z");
}

</style>
