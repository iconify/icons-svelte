<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xi253xtcz"/><path class="sjgt480pd"/><path class="vse8wy5nd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fruit-bowl-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sjgt480pd) {
  d: path("M6 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.vse8wy5nd) {
  d: path("M15 12c0 -4 2.5 -7 5 -7 0 4 -2.5 7 -5 7");
}

:global(.xi253xtcz) {
  d: path("M4 12h16c0 5 -4 9 -8 9s-8 -4 -8 -9");
}

</style>
