<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="bt_2bvgpa"/><path class="qcol0s9_v"/><path class="kavs8h2ql"/><path class="m5687cbde"/><path class="k6nj2fbya"/><path class="rkhcgsbdl"/><path class="o759xmblc"/><path class="wew0vnk_n"/><path class="k7cz9qivc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:normalize-data-duotone-thin" {...props}></Icon>
<style>
:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ck7sgubpk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.k7cz9qivc) {
  d: path("M18 11v5");
}

:global(.kavs8h2ql) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m5687cbde) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 11v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o759xmblc) {
  d: path("M6 8v8");
}

:global(.qcol0s9_v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.wew0vnk_n) {
  d: path("M12 5v14");
}

</style>
