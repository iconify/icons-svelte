<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y--9wccrh"/><path class="pkfzzlbbg"/><path class="jwxgs0b2c"/><path class="v4hj5197o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reading-light-outline-bold" {...props}></Icon>
<style>
:global(.jwxgs0b2c) {
  d: path("m11 9 4 -4");
}

:global(.pkfzzlbbg) {
  d: path("M11 9v11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v4hj5197o) {
  d: path("M10 9h8l-4 4Z");
}

:global(.y--9wccrh) {
  d: path("M5 20h12");
}

</style>
