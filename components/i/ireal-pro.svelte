<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uxc_w6bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ireal-pro" {...props}></Icon>
<style>
:global(.uxc_w6bqs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.066 20.999c12.682 3.01 5.453 14.411-14.055 11.591L37.74 7.464c9.132 7.589 10.384 21.144 2.796 30.276S19.393 48.124 10.26 40.536S-.124 19.393 7.464 10.261a21.5 21.5 0 0 1 24.98-6.033");
}

</style>
