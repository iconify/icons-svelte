<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l7lqi7bpl"/><path class="jmsypi7wx"/><path class="fain35bja"/><path class="hv6ejhb7e"/><path class="y5gdknoyt"/><path class="s6lrl6bmb"/><path class="xwfp38btc"/><path class="mfc7nxp-y"/><path class="ag9m5ebdy"/><path class="kp83gfxow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fasting-duotone-bold" {...props}></Icon>
<style>
:global(.ag9m5ebdy) {
  d: path("M12 7v13");
}

:global(.fain35bja) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hv6ejhb7e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jmsypi7wx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 4v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kp83gfxow) {
  d: path("M4 20 16 8");
}

:global(.l7lqi7bpl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 4v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mfc7nxp-y) {
  d: path("M9 7h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s6lrl6bmb) {
  d: path("M9 4v3");
}

:global(.xwfp38btc) {
  d: path("M15 4v3");
}

:global(.y5gdknoyt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20 16 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
