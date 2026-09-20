<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1t7h65-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-center" {...props}></Icon>
<style>
:global(.c1t7h65-t) {
  fill: currentColor;
  d: path("M3 12.5v-1h18v1zm4.5-3v-2h9v2zm0 7v-2h9v2z");
}

</style>
