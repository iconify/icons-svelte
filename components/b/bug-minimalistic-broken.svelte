<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s0k-qebzz"/><path class="ugk0bzb-s"/><path class="ksod32btv"/><path class="xpw199b1a"/><path class="okv-1ab4t"/><path class="pm3t8d4ps"/><path class="p472ttwxz"/><path class="jhanyibir"/><path class="enfo96b9n"/><path class="xdj171b8t"/><path class="gkzpwmxcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bug-minimalistic-broken" {...props}></Icon>
<style>
:global(.enfo96b9n) {
  d: path("M5.5 18.2002L3.5 19.0002");
}

:global(.gkzpwmxcg) {
  d: path("M10.5 15.5H13.5");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jhanyibir) {
  d: path("M18.5 18.2002L20.5 19.0002");
}

:global(.ksod32btv) {
  d: path("M5 13H2");
}

:global(.okv-1ab4t) {
  d: path("M5.29785 7.71909L3.50012 7");
}

:global(.p472ttwxz) {
  d: path("M9.5 3.5L7 2");
}

:global(.pm3t8d4ps) {
  d: path("M14.5 3.5L17 2");
}

:global(.s0k-qebzz) {
  d: path("M12 22C8.13401 22 5 18.866 5 15V10C5 6.13401 8.13401 3 12 3C15.866 3 19 6.13401 19 10V15C19 16.9587 18.1955 18.7295 16.899 20");
}

:global(.ugk0bzb-s) {
  d: path("M19 13H22");
}

:global(.xdj171b8t) {
  d: path("M10.5 10.5H13.5");
}

:global(.xpw199b1a) {
  d: path("M18.7021 7.71909L20.4999 7");
}

</style>
