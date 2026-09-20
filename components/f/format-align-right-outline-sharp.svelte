<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi037ib3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-align-right-outline-sharp" {...props}></Icon>
<style>
:global(.gi037ib3f) {
  fill: currentColor;
  d: path("M3 5V3h18v2zm6 4V7h12v2zm-6 4v-2h18v2zm6 4v-2h12v2zm-6 4v-2h18v2z");
}

</style>
