<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7h8iyqlm"/><path class="p2p_j61vf"/><path class="ownlczbmm"/><path class="pv52uob6b"/><path class="k4qo1xe9v"/><path class="hu2mwjewo"/><path class="l46p6bckm"/><path class="zka_zabrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bar-stool-duotone-thin" {...props}></Icon>
<style>
:global(.b7h8iyqlm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hu2mwjewo) {
  d: path("M12 6v10");
}

:global(.k4qo1xe9v) {
  d: path("M4 6h16");
}

:global(.l46p6bckm) {
  d: path("m8 20 4 -4 4 4");
}

:global(.ownlczbmm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 20 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p2p_j61vf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pv52uob6b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zka_zabrc) {
  d: path("M9 13h6");
}

</style>
