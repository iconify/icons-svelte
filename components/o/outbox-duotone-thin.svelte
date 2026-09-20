<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z0fx5ccnm"/><path class="sl6rqxyeh"/><path class="umzu2930r"/><path class="f-52c6b3g"/><path class="r_je2bdjk"/><path class="pp54i94hx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:outbox-duotone-thin" {...props}></Icon>
<style>
:global(.f-52c6b3g) {
  d: path("M4 10v10h16V10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pp54i94hx) {
  d: path("M9.5 5.5 12 3l2.5 2.5");
}

:global(.r_je2bdjk) {
  d: path("M12 4v5");
}

:global(.sl6rqxyeh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.umzu2930r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 5.5 12 3l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z0fx5ccnm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 10v10h16V10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
