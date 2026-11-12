<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr--8cbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:boolean-subtract-fill" {...props}></Icon>
<style>
:global(.rr--8cbus) {
  fill: currentColor;
  d: path("M14 2a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-4v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2Zm6 6a2 2 0 0 1 2 2v3a1 1 0 0 1-2 0v-3h-1a1 1 0 0 1 0-2Zm2 12a2 2 0 0 1-2 2h-3a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0Zm-9 0a1 1 0 0 1 0 2h-3a2 2 0 0 1-2-2v-1a1 1 0 0 1 2 0v1Z");
}

</style>
