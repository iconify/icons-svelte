<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yw989sb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:metro-de" {...props}></Icon>
<style>
:global(.yw989sb_z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5 9.071h12.214L24 22.643L30.786 9.07H43v29.86h-9.5V21.286l-6.786 17.643h-5.428L14.5 21.286v17.643H5z");
}

</style>
