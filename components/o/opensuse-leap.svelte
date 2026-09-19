<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="us1umflbw"/><path class="wd2fiznmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:opensuse-leap" {...props}></Icon>
<style>
:global(.us1umflbw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 5.5l14 14l-14 14l-14-14z");
}

:global(.wd2fiznmj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38 28.5l-14 14l-14-14");
}

</style>
