<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u73mekbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mode-comment-rounded" {...props}></Icon>
<style>
:global(.u73mekbwk) {
  fill: currentColor;
  d: path("M4 18q-.825 0-1.412-.587T2 16V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v15.575q0 .675-.612.938T20.3 20.3L18 18z");
}

</style>
