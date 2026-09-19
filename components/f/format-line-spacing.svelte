<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="siskydbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:format-line-spacing" {...props}></Icon>
<style>
:global(.siskydbba) {
  fill: currentColor;
  d: path("M6 7h2.5L5 3.5L1.5 7H4v10H1.5L5 20.5L8.5 17H6zm4-2v2h12V5zm0 14h12v-2H10zm0-6h12v-2H10z");
}

</style>
