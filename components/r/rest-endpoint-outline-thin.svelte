<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="to02llleg"/><path class="jroakeb3a"/><path class="pty_wsbvs"/><path class="lnqk7fb0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rest-endpoint-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jroakeb3a) {
  d: path("M17 4h4v16h-4");
}

:global(.lnqk7fb0y) {
  d: path("M8 15h5");
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

:global(.to02llleg) {
  d: path("M7 4H3v16h4");
}

</style>
