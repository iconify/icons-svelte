<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wmg_3zzyd"/><path class="v3wi5e3zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:quit-tracker" {...props}></Icon>
<style>
:global(.v3wi5e3zy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.646 26.848c.807-11.148 13.788.912 15.551-17.806");
}

:global(.wmg_3zzyd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 31.223h5.395v7.792H4.5zm9.629 0H43.5v7.792H14.129zm-9.553-4.356c3.316-16.68 14.68-1.68 15.934-17.882");
}

</style>
