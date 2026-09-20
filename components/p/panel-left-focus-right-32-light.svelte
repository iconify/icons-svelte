<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x0rjrmbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:panel-left-focus-right-32-light" {...props}></Icon>
<style>
:global(.x0rjrmbeo) {
  fill: currentColor;
  d: path("M2 8.5A4.5 4.5 0 0 1 6.5 4h19A4.5 4.5 0 0 1 30 8.5v15a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 23.5zM6.5 5A3.5 3.5 0 0 0 3 8.5v15A3.5 3.5 0 0 0 6.5 27H11V5z");
}

</style>
