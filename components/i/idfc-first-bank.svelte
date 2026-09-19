<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c2roa4baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:idfc-first-bank" {...props}></Icon>
<style>
:global(.c2roa4baz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h37v12.333h-37zm0 24.667h12.333V42.5H5.5zm0-12.334h24.667v12.333H5.5z");
}

</style>
