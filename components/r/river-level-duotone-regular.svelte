<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="cjx7a2bdd"/><path class="s4gag5t7u"/><path class="v6ewimfrm"/><path class="yzyen6bgh"/><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="f3zridcmg"/><path class="z_c7updjp"/><path class="m0msdy1bm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:river-level-duotone-regular" {...props}></Icon>
<style>
:global(.cjx7a2bdd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f3zridcmg) {
  d: path("m3 14 2.5 -2.5L8 14l2.5 -2.5L13 14l2.5 -2.5L18 14l2.5 -2.5");
}

:global(.m0msdy1bm) {
  d: path("M5 11h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pd-i35blz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s4gag5t7u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 14 2.5 -2.5L8 14l2.5 -2.5L13 14l2.5 -2.5L18 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v6ewimfrm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ws1d0fbts) {
  d: path("M20 4v16");
}

:global(.yzyen6bgh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z_c7updjp) {
  d: path("M5 8h4");
}

</style>
