<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d7ujgtb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:freshmile" {...props}></Icon>
<style>
:global(.d7ujgtb9s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 33.25A9.25 9.25 0 1 1 14.75 24H24zm0-18.5A9.25 9.25 0 1 1 33.25 24H24z");
}

</style>
