<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGeKYGyd1S)" class="w3o6o_kak"/><path fill="url(#SVGeKYGyd1S)" class="j3-9o7-pm"/><path fill="url(#SVG2kOC5d9h)" class="hdyv10_gt"/><path fill="url(#SVG2kOC5d9h)" class="hcrc1hb3w"/><path fill="url(#SVG5kxPGe2j)" class="bkjr7qaou"/><defs><linearGradient id="SVGeKYGyd1S" x1="4.746" x2="9.65" y1="8.391" y2="20.382" gradientUnits="userSpaceOnUse"><stop class="vwmmxyb8o"/><stop offset="1" class="y8_40qrsu"/></linearGradient><linearGradient id="SVG2kOC5d9h" x1="12.005" x2="12.005" y1="3" y2="11.99" gradientUnits="userSpaceOnUse"><stop class="tzy_3mmpl"/><stop offset="1" class="vgnkbubim"/></linearGradient><linearGradient id="SVG5kxPGe2j" x1="18.908" x2="14.403" y1="7.914" y2="21.005" gradientUnits="userSpaceOnUse"><stop class="ha5zssecr"/><stop offset="1" class="sth4tjb_q"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:land" {...props}></Icon>
<style>
:global(.bkjr7qaou) {
  d: path("M12.004 18.775L12.005 21l7.779-4.621V7.622L12.001 12l.002 4.377l5.835-3.404v2.432z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ha5zssecr) {
  stop-color: var(--svg-color--084bce, #084bce);
}

:global(.hcrc1hb3w) {
  d: path("M6.163 6.473L4.216 7.62l1.947 1.095z");
}

:global(.hdyv10_gt) {
  d: path("M8.109 5.325L12.049 3l7.734 4.622L12 12L8.109 9.81z");
}

:global(.j3-9o7-pm) {
  d: path("M8.109 9.812v4.377l3.89 2.189V12z");
}

:global(.sth4tjb_q) {
  stop-color: var(--svg-color--09166a, #09166a);
}

:global(.tzy_3mmpl) {
  stop-color: var(--svg-color--6695fe, #6695fe);
}

:global(.vgnkbubim) {
  stop-color: var(--svg-color--0b57e0, #0b57e0);
}

:global(.vwmmxyb8o) {
  stop-color: var(--svg-color--5c93f7, #5c93f7);
}

:global(.w3o6o_kak) {
  d: path("M6.163 8.717v6.664L12 18.776V21l-7.784-4.62V7.622z");
}

:global(.y8_40qrsu) {
  stop-color: var(--svg-color--1159df, #1159df);
}

</style>
