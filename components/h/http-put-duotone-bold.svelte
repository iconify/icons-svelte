<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="u4bivyvge"/><path class="za1ermbcy"/><path class="ob_gyjbjx"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="rjyodzkad"/><path class="a9txaac_h"/><path class="j4d2337wb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:http-put-duotone-bold" {...props}></Icon>
<style>
:global(.a9txaac_h) {
  d: path("M12 10.5V16");
}

:global(.c1kziyotx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.hieqhxiaw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j4d2337wb) {
  d: path("m9.5 13 2.5 -2.5 2.5 2.5");
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.ob_gyjbjx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 13 2.5 -2.5 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rjyodzkad) {
  d: path("M9.5 7.5h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u4bivyvge) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 7.5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.za1ermbcy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10.5V16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
