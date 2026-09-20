<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud0wm_1vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:post-add-outline-sharp" {...props}></Icon>
<style>
:global(.ud0wm_1vo) {
  fill: currentColor;
  d: path("M8 10.5v-1h7v1zm0 3v-1h7v1zm0 3v-1h7v1zM17.5 8V6h-2V5h2V3h1v2h2v1h-2v2zm-14 12V4h10.923v1H4.5v14h14V9.077h1V20z");
}

</style>
