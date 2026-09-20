<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qv6cnabrq"/><path class="oqj-o0b2r"/><path class="ktxjg3b2q"/><path class="evsu0jbbm"/><path class="drjad9bfe"/><path class="zpusjcvvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rake-outline-regular" {...props}></Icon>
<style>
:global(.drjad9bfe) {
  d: path("M14 14v4");
}

:global(.evsu0jbbm) {
  d: path("M10 14v4");
}

:global(.ktxjg3b2q) {
  d: path("M6 14v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqj-o0b2r) {
  d: path("M5 14h14");
}

:global(.qv6cnabrq) {
  d: path("M12 3v11");
}

:global(.zpusjcvvn) {
  d: path("M18 14v4");
}

</style>
