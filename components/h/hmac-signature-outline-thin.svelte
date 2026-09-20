<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xfs8wlfhn"/><path class="ygr1bbcag"/><path class="u7m7z6ojw"/><path class="v33uslbhb"/><path class="ypkzbabdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hmac-signature-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u7m7z6ojw) {
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.v33uslbhb) {
  d: path("M12 16v2.5");
}

:global(.xfs8wlfhn) {
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.ygr1bbcag) {
  d: path("M8 9.5a4 4 0 0 1 8 0");
}

:global(.ypkzbabdh) {
  d: path("M12 17h2.5");
}

</style>
