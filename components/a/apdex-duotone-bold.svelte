<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="wg9mubc5k"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="orhpjmvzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:apdex-duotone-bold" {...props}></Icon>
<style>
:global(.dh-nlhghu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.orhpjmvzo) {
  d: path("M7 7h4v4h4v4h4");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wg9mubc5k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 7h4v4h4v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
