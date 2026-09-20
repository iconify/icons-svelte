<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rexb17ada"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:picture-in-picture-32-regular" {...props}></Icon>
<style>
:global(.rexb17ada) {
  fill: currentColor;
  d: path("M28 17a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-9a3 3 0 0 1-3-3v-7a3 3 0 0 1 3-3zM25.5 3A4.5 4.5 0 0 1 30 7.5v8.468a4.5 4.5 0 0 0-2-.468v-8A2.5 2.5 0 0 0 25.5 5h-19A2.5 2.5 0 0 0 4 7.5v15A2.5 2.5 0 0 0 6.5 25h8v2h-8A4.5 4.5 0 0 1 2 22.5v-15A4.5 4.5 0 0 1 6.5 3z");
}

</style>
