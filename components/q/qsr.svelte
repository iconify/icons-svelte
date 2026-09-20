<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGPIz9hcuM)" class="kouw2db_q"/><defs><linearGradient id="SVGPIz9hcuM" x1="4.687" x2="19.312" y1="5.25" y2="19.875" gradientUnits="userSpaceOnUse"><stop class="l44tr8bke"/><stop offset=".18" class="b9avsib0j"/><stop offset=".38" class="n_kyw6brh"/><stop offset=".5" class="wnfur-bji"/><stop offset=".65" class="qs1040l3v"/><stop offset=".82" class="k52mwnbbf"/><stop offset="1" class="g8koxjb3i"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:qsr" {...props}></Icon>
<style>
:global(.b9avsib0j) {
  stop-color: var(--svg-color--54bcf0, #54bcf0);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g8koxjb3i) {
  stop-color: var(--svg-color--a745f4, #a745f4);
}

:global(.k52mwnbbf) {
  stop-color: var(--svg-color--51bcf4, #51bcf4);
}

:global(.kouw2db_q) {
  d: path("m16.477 21l-5.04-9.281L3 7.635v-.698A3.937 3.937 0 0 1 6.937 3h.585l5.04 9.281L21 16.236v.826A3.937 3.937 0 0 1 17.063 21z");
}

:global(.l44tr8bke) {
  stop-color: var(--svg-color--a745f5, #a745f5);
}

:global(.n_kyw6brh) {
  stop-color: var(--svg-color--99e5c5, #99e5c5);
}

:global(.qs1040l3v) {
  stop-color: var(--svg-color--91e1c8, #91e1c8);
}

:global(.wnfur-bji) {
  stop-color: var(--svg-color--fffcd8, #fffcd8);
}

</style>
