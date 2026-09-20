<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e8i7n8dqg"/><path class="km2_vvbqp"/><path class="wdfpsmk4k"/><path class="pmz-ctb8u"/><path class="dpia4433y"/><path class="azjtlhb3x"/><path class="o8od38cnm"/><path class="hiqcqfbaf"/><path class="rqk3146zh"/><path class="uysczfb3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:island-duotone-bold" {...props}></Icon>
<style>
:global(.azjtlhb3x) {
  d: path("M4 18a8 8 0 0 1 16 0");
}

:global(.dpia4433y) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 11a3 3 0 0 1 0 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e8i7n8dqg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hiqcqfbaf) {
  d: path("M12 8v10");
}

:global(.km2_vvbqp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.pmz-ctb8u) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 5a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rqk3146zh) {
  d: path("M9 5a3 3 0 0 1 0 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uysczfb3e) {
  d: path("M15 11a3 3 0 0 1 0 -6");
}

:global(.wdfpsmk4k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
