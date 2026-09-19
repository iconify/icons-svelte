<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u3aa9vbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:freeotp" {...props}></Icon>
<style>
:global(.u3aa9vbzy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5L7.11 14.25v19.5L24 43.5l16.89-9.75v-19.5ZM7.11 14.25L24 24m0 19.5V24m16.89-9.75L24 24");
}

</style>
