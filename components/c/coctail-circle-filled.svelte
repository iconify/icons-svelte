<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGfJrAlctK"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="l7q_6ridl"/><path clip-rule="evenodd" class="cqlc-ibyw"/><path class="loe9to26g"/><path class="g_oknzbvo"/><path class="v7o86obex"/></g></mask></defs><circle mask="url(#SVGfJrAlctK)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:coctail-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.cqlc-ibyw) {
  fill-rule: evenodd;
  d: path("m5.767 8.68l6.5 7a1 1 0 0 0 1.466 0l6.5-7c.594-.64.14-1.68-.733-1.68h-13c-.873 0-1.327 1.04-.733 1.68m11.44.32L13 13.53L8.793 9z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g_oknzbvo) {
  d: path("M17.5 23h-9c0-1.475 2.05-2.5 4.5-2.5s4.5 1.025 4.5 2.5M15.818 4.728a.75.75 0 0 1 .364-1.456l4 1a.75.75 0 0 1-.364 1.456z");
}

:global(.ivjvz2eii) {
  fill: var(--svg-color--000, #000);
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.l7q_6ridl) {
  d: path("M9 11a.5.5 0 0 1 0-1h8a.5.5 0 0 1 0 1z");
}

:global(.loe9to26g) {
  d: path("M14 14.5v7h-2v-7z");
}

:global(.v7o86obex) {
  d: path("M14.212 11.737a.75.75 0 1 1-1.424-.474l2.5-7.5a.75.75 0 1 1 1.424.474z");
}

</style>
