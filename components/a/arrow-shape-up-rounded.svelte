<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynttzcbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-shape-up-rounded" {...props}></Icon>
<style>
:global(.ynttzcbuu) {
  fill: currentColor;
  d: path("M8.539 19.192v-5H5.325q-.379 0-.55-.348t.09-.646L11.399 5.7q.243-.279.602-.279t.602.279l6.533 7.498q.261.298.09.646t-.55.348h-3.213v5q0 .349-.23.578t-.578.23H9.346q-.348 0-.578-.23t-.23-.578");
}

</style>
