<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mw3edqbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-line-16-filled" {...props}></Icon>
<style>
:global(.mw3edqbts) {
  fill: currentColor;
  d: path("M14.98 8.5a6.999 6.999 0 0 1-13.96 0zM8 1a7 7 0 0 1 6.98 6.5H1.02A7 7 0 0 1 8 1");
}

</style>
