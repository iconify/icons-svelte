<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lvbrlvbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:align-left-32-filled" {...props}></Icon>
<style>
:global(.lvbrlvbly) {
  fill: currentColor;
  d: path("M3 4a1 1 0 0 1 2 0v24a1 1 0 1 1-2 0zm7.5 1A3.5 3.5 0 0 0 7 8.5v3a3.5 3.5 0 0 0 3.5 3.5h15a3.5 3.5 0 0 0 3.5-3.5v-3A3.5 3.5 0 0 0 25.5 5zm0 12A3.5 3.5 0 0 0 7 20.5v3a3.5 3.5 0 0 0 3.5 3.5h9a3.5 3.5 0 0 0 3.5-3.5v-3a3.5 3.5 0 0 0-3.5-3.5z");
}

</style>
