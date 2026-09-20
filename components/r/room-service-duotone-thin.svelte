<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsu8hn7ln"/><path class="xawcw5elo"/><path class="bpah47shs"/><path class="drz60ab5x"/><path class="ils7yp4cg"/><path class="bv1y61bvs"/><path class="us2evabuy"/><path class="qw7b_6b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:room-service-duotone-thin" {...props}></Icon>
<style>
:global(.bpah47shs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5.5V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bv1y61bvs) {
  d: path("M4 16a8 8 0 0 1 16 0");
}

:global(.drz60ab5x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 20h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ils7yp4cg) {
  d: path("M2 16h20");
}

:global(.qw7b_6b1t) {
  d: path("M8 20h8");
}

:global(.rsu8hn7ln) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.us2evabuy) {
  d: path("M12 5.5V8");
}

:global(.xawcw5elo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 16a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
