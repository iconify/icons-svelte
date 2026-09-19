<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drwso0xuh"/><path class="rsxj5waol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-smart-screen" {...props}></Icon>
<style>
:global(.drwso0xuh) {
  fill: currentColor;
  d: path("M21 5H3c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2m-3 12H6V7h12z");
}

:global(.rsxj5waol) {
  fill: currentColor;
  d: path("M15 11.25h1.5v1.5H15zm-2.5 0H14v1.5h-1.5zm-2.5 0h1.5v1.5H10zm-2.5 0H9v1.5H7.5z");
}

</style>
