<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ef_kgbbrh"/><path class="i5b-c6tma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:exd" {...props}></Icon>
<style>
:global(.ef_kgbbrh) {
  fill: var(--svg-color--ec793e, #ec793e);
  d: path("M5.4 3h4.8v18H5.4z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.i5b-c6tma) {
  fill: var(--svg-color--0d1122, #0d1122);
  d: path("M18.6 3h-7.8l7.8 7.2zm0 18v-7.2L10.8 21z");
}

</style>
