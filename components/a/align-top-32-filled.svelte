<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ylzri3bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:align-top-32-filled" {...props}></Icon>
<style>
:global(.ylzri3bcz) {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 0 0 2h24a1 1 0 1 0 0-2zm1 7.5A3.5 3.5 0 0 1 8.5 7h3a3.5 3.5 0 0 1 3.5 3.5v15a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 5 25.5zm12 0A3.5 3.5 0 0 1 20.5 7h3a3.5 3.5 0 0 1 3.5 3.5v9a3.5 3.5 0 0 1-3.5 3.5h-3a3.5 3.5 0 0 1-3.5-3.5z");
}

</style>
