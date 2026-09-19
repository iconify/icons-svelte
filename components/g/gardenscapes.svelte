<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g5bpdccdu"/><path class="nxderxbdv"/><path class="aw_iv2bgd"/><path class="bw_qucbfz"/><path class="k9iautbba"/><path class="t72xrbckf"/><path class="wk4m6ebum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gardenscapes" {...props}></Icon>
<style>
:global(.aw_iv2bgd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.164 23.914c-2.997-4.768-8.002-3.862-7.45-9.577c.551-5.714 9.926-9.344 11.741 4.058");
}

:global(.bw_qucbfz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.304 27.116c-5.408-.916-17.231.109-16.246-4.739s6.73-4.915 12.82-2.384");
}

:global(.g5bpdccdu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.64 21.74c-3.586 0-6.384 1.898-6.384 4.696s1.97 2.76 3.704 2.76s5.833-1.505 5.833-3.728s-1.064-3.728-3.153-3.728");
}

:global(.k9iautbba) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.706 28.967C16.561 33.389 8.96 38.114 6.25 33.45c-1.694-2.916.75-5.568 5.518-6.941m11.192 2.686c-.998 4.545 3.18 12.073 8.263 7.265s.371-8.283-3.223-9.344");
}

:global(.nxderxbdv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.063 22.855s2.543-3.315 5.617-5.601s2.404-7.803-2.325-7.803c-3.508 0-7.85 3.801-6.743 12.344");
}

:global(.t72xrbckf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.706 28.967c-.642 2.581-9.897 6.783-5.129 9.522c1.255.72 5.78.43 8.447-3.306m4.769-9.715c6.608-3.826 14.096-4.812 13.78 1.297s-7.671 4.415-9.904 3.33");
}

:global(.wk4m6ebum) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.452 17.426c3.801-2.8 11.052-5.162 11.525 0s-6.616 4.61-8.783 5.15");
}

</style>
