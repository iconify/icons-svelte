<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zzrqoqm8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:meshtastic" {...props}></Icon>
<style>
:global(.zzrqoqm8m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 32.667l13-17.334m26 17.334l-13-17.334l-13 17.334");
}

</style>
