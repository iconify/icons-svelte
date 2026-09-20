<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sch2pmb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:poll-32-filled" {...props}></Icon>
<style>
:global(.sch2pmb3a) {
  fill: currentColor;
  d: path("M12 6.5a3.5 3.5 0 1 1 7 0v19a3.5 3.5 0 1 1-7 0zM25.5 9a3.5 3.5 0 0 0-3.5 3.5v13a3.5 3.5 0 1 0 7 0v-13A3.5 3.5 0 0 0 25.5 9M2 18.5a3.5 3.5 0 1 1 7 0v7a3.5 3.5 0 1 1-7 0z");
}

</style>
