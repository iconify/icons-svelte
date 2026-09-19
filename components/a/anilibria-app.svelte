<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b5gwtsb9z"/><path class="udb3x2b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:anilibria-app" {...props}></Icon>
<style>
:global(.b5gwtsb9z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.649 31.611L24.696 41.926m-13.024.574L23.836 5.536L34.612 42.5");
}

:global(.udb3x2b6h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.352 5.5l16.522 29.255l15.468-10.11");
}

</style>
