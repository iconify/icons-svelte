<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6nb14bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-legend-toggle" {...props}></Icon>
<style>
:global(.q6nb14bed) {
  fill: currentColor;
  d: path("M20 15H4v-2h16zm0 2H4v2h16zm-5-6l5-3.55V5l-5 3.55L10 5L4 8.66V11l5.92-3.61z");
}

</style>
