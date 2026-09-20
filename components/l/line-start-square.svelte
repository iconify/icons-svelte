<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh36n-rss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-start-square" {...props}></Icon>
<style>
:global(.dh36n-rss) {
  fill: currentColor;
  d: path("M13 17.5H2v-11h11V11h9v2h-9z");
}

</style>
