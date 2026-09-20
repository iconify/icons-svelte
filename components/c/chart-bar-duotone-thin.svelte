<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="lujrvhf4j"/><path class="ald7lxbvs"/><path class="sh-bzloxt"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="d4s5t4bpo"/><path class="y4-ssjnrw"/><path class="j4if4rbfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-bar-duotone-thin" {...props}></Icon>
<style>
:global(.ald7lxbvs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d4s5t4bpo) {
  d: path("M8 12v8");
}

:global(.gms_xv68n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j4if4rbfv) {
  d: path("M18 14v6");
}

:global(.lujrvhf4j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.sh-bzloxt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y4-ssjnrw) {
  d: path("M13 8v12");
}

:global(.yu-j7jb_g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
