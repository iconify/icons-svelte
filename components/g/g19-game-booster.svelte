<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ryr7xt5_p"/><path class="imsfdmbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:g19-game-booster" {...props}></Icon>
<style>
:global(.imsfdmbmj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.507 30.723L24 24l10.46 6.655");
}

:global(.ryr7xt5_p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.898 43.5c-.586-.003-16.564-9.33-16.854-9.838c-.29-.509-.193-18.995.102-19.5c.296-.506 16.37-9.665 16.956-9.662s16.564 9.33 16.854 9.838c.29.509.193 18.995-.102 19.5c-.296.505-16.37 9.665-16.956 9.662M24 12.23V24");
}

</style>
