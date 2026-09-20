<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="brcw6lb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:hexagon-48-filled" {...props}></Icon>
<style>
:global(.brcw6lb2y) {
  fill: currentColor;
  d: path("M15.427 6a3.25 3.25 0 0 0-2.84 1.67L4.38 22.42a3.25 3.25 0 0 0 0 3.16l8.207 14.75a3.25 3.25 0 0 0 2.84 1.67h17.148a3.25 3.25 0 0 0 2.84-1.67l8.208-14.75a3.25 3.25 0 0 0 0-3.16L35.415 7.67A3.25 3.25 0 0 0 32.575 6z");
}

</style>
