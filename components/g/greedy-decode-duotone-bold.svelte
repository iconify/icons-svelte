<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="be5gt_bmt"/><path class="fuo4460wo"/><path class="tpkouhbgu"/><path class="hyrj3cfwo"/><path class="ytqok-bxz"/><path class="gorvssbqo"/><path class="e6cqo_biq"/><path class="kliut9bht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:greedy-decode-duotone-bold" {...props}></Icon>
<style>
:global(.be5gt_bmt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h15.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e6cqo_biq) {
  d: path("m6 12 5 -5");
}

:global(.fuo4460wo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17.5 9.5 20 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gorvssbqo) {
  d: path("M17.5 9.5 20 12l-2.5 2.5");
}

:global(.hyrj3cfwo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 12 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kliut9bht) {
  d: path("m10 12 5 5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tpkouhbgu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 12 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ytqok-bxz) {
  d: path("M2 12h15.5");
}

</style>
