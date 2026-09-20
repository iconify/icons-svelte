<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jd_dotbnq"/><path class="h2fnwccfy"/><path class="po2el86ye"/><path class="y_2nr8hoa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:log-parse-outline-thin" {...props}></Icon>
<style>
:global(.h2fnwccfy) {
  d: path("M7 6h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jd_dotbnq) {
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
}

:global(.po2el86ye) {
  d: path("M12 9v5.5");
}

:global(.y_2nr8hoa) {
  d: path("m9.5 12 2.5 2.5 2.5 -2.5");
}

</style>
