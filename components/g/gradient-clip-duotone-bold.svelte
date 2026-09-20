<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fpgwa74dn"/><path class="k_aforbjf"/><path class="poy74vb0a"/><path class="fain35bja"/><path class="tu8ll15ii"/><path class="n_s7qxbob"/><path class="c4ap_p0of"/><path class="s2ui7wbye"/><path class="mfc7nxp-y"/><path class="du_3_4tit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gradient-clip-duotone-bold" {...props}></Icon>
<style>
:global(.c4ap_p0of) {
  d: path("M12 4v15");
}

:global(.du_3_4tit) {
  d: path("M4 21.5h16");
}

:global(.fain35bja) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fpgwa74dn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k_aforbjf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mfc7nxp-y) {
  d: path("M9 7h6");
}

:global(.n_s7qxbob) {
  d: path("M6 10v9");
}

:global(.poy74vb0a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s2ui7wbye) {
  d: path("M18 12v7");
}

:global(.tu8ll15ii) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 21.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
