<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pemn838wn"/><path class="ia4sldbfw"/><path class="uepfj3b0o"/><path class="lx6fvk9xv"/><path class="gku_y1i9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:insurance-broker-outline-thin" {...props}></Icon>
<style>
:global(.gku_y1i9j) {
  d: path("M12 17.5V20");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ia4sldbfw) {
  d: path("M3 21a9 9 0 0 1 18 0");
}

:global(.lx6fvk9xv) {
  d: path("M8.5 17.5h7");
}

:global(.pemn838wn) {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.uepfj3b0o) {
  d: path("M8.5 17.5a3.5 3.5 0 0 1 7 0");
}

</style>
