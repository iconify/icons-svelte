<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av79orfll"/><path class="kw3mck_6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-airplay" {...props}></Icon>
<style>
:global(.av79orfll) {
  fill: currentColor;
  d: path("M6 22h12l-6-6z");
}

:global(.kw3mck_6h) {
  fill: currentColor;
  d: path("M21 3H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h4v-2H3V5h18v12h-4v2h4c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2");
}

</style>
