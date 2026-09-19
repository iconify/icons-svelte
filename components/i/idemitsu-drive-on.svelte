<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wwflqn3gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:idemitsu-drive-on" {...props}></Icon>
<style>
:global(.wwflqn3gw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 38.5h37L24 9.5zm17.344-16.313h-6.938m10.406 5.438H12.436m17.345 5.437H8.969");
}

</style>
