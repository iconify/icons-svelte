<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sty4y45ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:doorbell-fill" {...props}></Icon>
<style>
:global(.sty4y45ls) {
  fill: currentColor;
  d: path("M8 2h8a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m6 5h-4a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2m-5 7a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
