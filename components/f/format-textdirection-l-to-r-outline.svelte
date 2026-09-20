<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scg07fvgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-textdirection-l-to-r-outline" {...props}></Icon>
<style>
:global(.scg07fvgv) {
  fill: currentColor;
  d: path("M9 15v-5q-1.65 0-2.825-1.175T5 6t1.175-2.825T9 2h8v2h-2v11h-2V4h-2v11zm0-7V4q-.825 0-1.412.588T7 6t.588 1.413T9 8m8 14l-1.4-1.4l1.6-1.6H3v-2h14.2l-1.6-1.6L17 14l4 4z");
}

</style>
