<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uss4u8bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:app-shortcut-sharp" {...props}></Icon>
<style>
:global(.uss4u8bil) {
  fill: currentColor;
  d: path("M17.15 13H12v3h-2v-5h7.15L15.6 9.4L17 8l4 4l-4 4l-1.4-1.4zM5 23V1h14v6h-2V6H7v12h10v-1h2v6z");
}

</style>
