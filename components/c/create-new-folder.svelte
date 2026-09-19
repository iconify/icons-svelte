<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu6miob5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:create-new-folder" {...props}></Icon>
<style>
:global(.lu6miob5y) {
  fill: currentColor;
  d: path("M20 6h-8l-2-2H4c-1.11 0-1.99.89-1.99 2L2 18c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V8c0-1.11-.89-2-2-2m-1 8h-3v3h-2v-3h-3v-2h3V9h2v3h3z");
}

</style>
