<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d58q_4bdh"/><path class="fg-hc3ysv"/><path class="japrfgbml"/><path class="c3xus2otf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:check-read-broken" {...props}></Icon>
<style>
:global(.c3xus2otf) {
  stroke-linejoin: round;
  d: path("M11 16L11.4283 16.5625L13.5712 14.3125M15.7142 12.0625L20 7.5625");
}

:global(.d58q_4bdh) {
  d: path("M4 12.8999L7.14286 16.4999");
}

:global(.fg-hc3ysv) {
  d: path("M7.14258 16.5L9.10686 14.25");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.japrfgbml) {
  d: path("M11.0713 12L14.9999 7.5");
}

</style>
