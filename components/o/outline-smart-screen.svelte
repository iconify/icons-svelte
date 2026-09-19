<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faab-lbtd"/><path class="idwqf0d1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-smart-screen" {...props}></Icon>
<style>
:global(.faab-lbtd) {
  fill: currentColor;
  d: path("M12.5 11.25H14v1.5h-1.5zm2.5 0h1.5v1.5H15zm-5 0h1.5v1.5H10zm-2.5 0H9v1.5H7.5z");
}

:global(.idwqf0d1x) {
  fill: currentColor;
  d: path("M21 5H3c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2M4 17H3V7h1zm14 0H6V7h12zm3 0h-1V7h1z");
}

</style>
