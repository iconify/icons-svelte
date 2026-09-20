<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c09pv4beg"/><path class="y5hpikbvp"/><path class="nq3y51bfw"/><path class="ddoll-bvi"/><path class="beqem0mpw"/><path class="ghf2zyulc"/><path class="lpi5lkbmw"/><path class="wr9epib_z"/><path class="ka1ksx6kt"/><path class="u649he-6w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ddos-duotone-thin" {...props}></Icon>
<style>
:global(.beqem0mpw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c09pv4beg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ddoll-bvi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ghf2zyulc) {
  d: path("M2 5h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ka1ksx6kt) {
  d: path("M2 19h12");
}

:global(.lpi5lkbmw) {
  d: path("M2 9h12");
}

:global(.nq3y51bfw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u649he-6w) {
  d: path("M18 3v18");
}

:global(.wr9epib_z) {
  d: path("M2 15h12");
}

:global(.y5hpikbvp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 9h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
