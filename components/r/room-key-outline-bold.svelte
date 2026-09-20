<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ix51aqbzd"/><path class="mrzdbhb5c"/><path class="xbbf36buj"/><path class="y4tlj9bad"/><path class="w8gxvdb9g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:room-key-outline-bold" {...props}></Icon>
<style>
:global(.ix51aqbzd) {
  d: path("M3.5 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

:global(.mrzdbhb5c) {
  d: path("M7 13.5V21");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w8gxvdb9g) {
  d: path("M14 8h5");
}

:global(.xbbf36buj) {
  d: path("M7 18h4");
}

:global(.y4tlj9bad) {
  d: path("M12 5h9v6h-9Z");
}

</style>
