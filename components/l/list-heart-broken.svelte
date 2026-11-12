<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zziv607bu"/><path class="v3bnzubkl"/><path class="s5xpay_7j"/><path class="tnwts_9gl"/><path class="a2rh-x5uk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-heart-broken" {...props}></Icon>
<style>
:global(.a2rh-x5uk) {
  d: path("M20 10L9.5 10M3 10H5.25");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s5xpay_7j) {
  d: path("M10 18H3");
}

:global(.tnwts_9gl) {
  d: path("M3 6L13.5 6M20 6L17.75 6");
}

:global(.v3bnzubkl) {
  d: path("M10 14H3");
}

:global(.zziv607bu) {
  stroke-linejoin: round;
  d: path("M14 15.0361C14 16.2709 15.4849 17.5789 16.5203 18.3408C16.9546 18.6603 17.1717 18.8201 17.5 18.8201C17.8283 18.8201 18.0454 18.6603 18.4797 18.3408C19.5151 17.5789 21 16.2709 21 15.0361C21 13.0282 19.0749 12.2786 17.5 13.8296C15.9251 12.2786 14 13.0282 14 15.0361Z");
}

</style>
