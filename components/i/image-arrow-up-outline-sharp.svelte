<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k46mvkbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:image-arrow-up-outline-sharp" {...props}></Icon>
<style>
:global(.k46mvkbga) {
  fill: currentColor;
  d: path("M4 20V4h9.154v1H5v14h14v-7.058h1V20zm3.5-3.5h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zm10.712-6.711V4.92l-2.1 2.056l-.689-.688L18.712 3L22 6.289l-.688.688l-2.1-2.056V9.79z");
}

</style>
