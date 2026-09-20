<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k7xqwbc0e"/><path class="m1_t8eblw"/><path class="g-jmfdcne"/><path class="p53i0is_x"/><path class="q84dtjb2k"/><path class="ghf2zyulc"/><path class="lpi5lkbmw"/><path class="wr9epib_z"/><path class="ka1ksx6kt"/><path class="u649he-6w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ddos-duotone-bold" {...props}></Icon>
<style>
:global(.g-jmfdcne) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ghf2zyulc) {
  d: path("M2 5h12");
}

:global(.k7xqwbc0e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ka1ksx6kt) {
  d: path("M2 19h12");
}

:global(.lpi5lkbmw) {
  d: path("M2 9h12");
}

:global(.m1_t8eblw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 9h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p53i0is_x) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q84dtjb2k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u649he-6w) {
  d: path("M18 3v18");
}

:global(.wr9epib_z) {
  d: path("M2 15h12");
}

</style>
