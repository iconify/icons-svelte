<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eilgs0b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crossword-outline-sharp" {...props}></Icon>
<style>
:global(.eilgs0b3u) {
  fill: currentColor;
  d: path("M10 20h4v-4h-4zm-6-6h4v-4H4zm6 0h4v-4h-4zm6 0h4v-4h-4zm0-6h4V4h-4zM8 22v-6H2V8h12V2h8v14h-6v6z");
}

</style>
