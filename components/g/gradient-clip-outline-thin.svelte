<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_s7qxbob"/><path class="c4ap_p0of"/><path class="s2ui7wbye"/><path class="mfc7nxp-y"/><path class="du_3_4tit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gradient-clip-outline-thin" {...props}></Icon>
<style>
:global(.c4ap_p0of) {
  d: path("M12 4v15");
}

:global(.du_3_4tit) {
  d: path("M4 21.5h16");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mfc7nxp-y) {
  d: path("M9 7h6");
}

:global(.n_s7qxbob) {
  d: path("M6 10v9");
}

:global(.s2ui7wbye) {
  d: path("M18 12v7");
}

</style>
