<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtwwe_b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:resume-outline" {...props}></Icon>
<style>
:global(.rtwwe_b8w) {
  fill: currentColor;
  d: path("M6 18V6h2v12zm4 0l10-6l-10-6zm2-3.525v-4.95L16.125 12zM12 12");
}

</style>
