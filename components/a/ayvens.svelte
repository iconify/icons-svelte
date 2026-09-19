<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nif4mac9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ayvens" {...props}></Icon>
<style>
:global(.nif4mac9s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.566 9.467c0 16.053-13.013 29.066-29.066 29.066L26.35 9.467zm1.972 0H43.5v29.066H30.735c4.922-9.998 4.803-29.066 4.803-29.066");
}

</style>
