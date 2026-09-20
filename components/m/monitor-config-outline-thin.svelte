<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jq9hovbrs"/><path class="m7p35uguv"/><path class="qdn88l2uv"/><path class="pty_wsbvs"/><path class="se-xbgbbm"/><path class="d1t4ffbbq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:monitor-config-outline-thin" {...props}></Icon>
<style>
:global(.d1t4ffbbq) {
  d: path("M8 12.5h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jq9hovbrs) {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.m7p35uguv) {
  d: path("M12 17v3");
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

:global(.qdn88l2uv) {
  d: path("M7 20h10");
}

:global(.se-xbgbbm) {
  d: path("M13.5 7v4");
}

</style>
