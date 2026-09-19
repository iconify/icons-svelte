<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wytnhjb-q"/><path class="stz8zevtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ntfy" {...props}></Icon>
<style>
:global(.stz8zevtx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.227 27.878l10.282-5.945l-10.282-5.945m13.139 13.094h10.96");
}

:global(.wytnhjb-q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.719 7.784a4.483 4.483 0 0 0-4.49 4.496v20.185a4.5 4.5 0 0 0 .166 1.202L4.5 40.216l12.294-3.255H39.01a4.483 4.483 0 0 0 4.49-4.496V12.28a4.483 4.483 0 0 0-4.49-4.496Z");
}

</style>
