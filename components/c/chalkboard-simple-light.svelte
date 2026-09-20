<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="u17d709tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:chalkboard-simple-light" {...props}></Icon>
<style>
:global(.u17d709tb) {
  fill: currentColor;
  d: path("M240 194h-10v-26a6 6 0 0 0-6-6h-64a6 6 0 0 0-6 6v26H38V56a2 2 0 0 1 2-2h176a2 2 0 0 1 2 2v80a6 6 0 0 0 12 0V56a14 14 0 0 0-14-14H40a14 14 0 0 0-14 14v138H16a6 6 0 0 0 0 12h224a6 6 0 0 0 0-12m-74-20h52v20h-52Z");
}

</style>
