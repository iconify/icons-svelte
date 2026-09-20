<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_0h8cbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:move-group-sharp" {...props}></Icon>
<style>
:global(.f_0h8cbmq) {
  fill: currentColor;
  d: path("M6 18v-4h2v2h12V6H8v2H6V2h16v16zm-4 4V6h2v14h14v2zm11-7l-1.4-1.4l1.575-1.6H6v-2h7.175L11.6 8.4L13 7l4 4z");
}

</style>
