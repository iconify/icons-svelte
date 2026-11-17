<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cga0snbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fire-extinguisher-fill-round" {...props}></Icon>
<style>
:global(.cga0snbtr) {
  fill: currentColor;
  d: path("M12 7.099V6H9a3 3 0 0 0-3 3v7a1 1 0 0 1-2 0V9a5 5 0 0 1 5-5h3.838l5.846-1.949a1.001 1.001 0 0 1 .632 1.898L14 5.721v1.378A5.01 5.01 0 0 1 18 12v2H8v-2a5.01 5.01 0 0 1 4-4.901M8 17v-1h10v1a5 5 0 0 1-10 0");
}

</style>
