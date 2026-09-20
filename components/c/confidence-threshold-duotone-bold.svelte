<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="li29erb7r"/><path class="zndks8byv"/><path class="bp-bj-6is"/><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="okds9dbso"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e_6o-gbms"/><path class="h857n5bhq"/><path class="qrffjub9u"/><path class="t164-vbgd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:confidence-threshold-duotone-bold" {...props}></Icon>
<style>
:global(.bp-bj-6is) {
  fill: currentColor;
  d: path("M16 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dh-nlhghu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e_6o-gbms) {
  d: path("M6 10h13");
}

:global(.h857n5bhq) {
  d: path("M8 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.li29erb7r) {
  fill: currentColor;
  d: path("M8 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.okds9dbso) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qrffjub9u) {
  d: path("M12 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.t164-vbgd) {
  d: path("M16 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zndks8byv) {
  fill: currentColor;
  d: path("M12 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
