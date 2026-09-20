<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhkjxts0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:ripples-outline-sharp" {...props}></Icon>
<style>
:global(.zhkjxts0k) {
  fill: currentColor;
  d: path("M5 19h14V9.873q-.45.294-.953.46T17 10.5q-1.458 0-2.479-1.021T13.5 7q0-.544.166-1.047q.167-.503.461-.953H5zm-1 1V4h16v16zM5 5v14z");
}

</style>
