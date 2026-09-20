<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kbuw3obvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cursor-16-filled" {...props}></Icon>
<style>
:global(.kbuw3obvj) {
  fill: currentColor;
  d: path("M4.002 2.998a1 1 0 0 1 1.6-.8L13.6 8.2c.768.576.36 1.8-.6 1.8H9.053a1 1 0 0 0-.793.39l-2.466 3.215c-.581.758-1.793.347-1.793-.609z");
}

</style>
