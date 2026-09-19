<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fskv5_56t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:eksi-sozluk" {...props}></Icon>
<style>
:global(.fskv5_56t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.533 29.967c0 7.474-6.06 13.533-13.533 13.533s-13.533-6.059-13.533-13.533C10.467 19.094 24 4.5 24 4.5s13.533 14.594 13.533 25.467");
}

</style>
