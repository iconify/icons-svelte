<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t-2qmb_5w"/><path class="tp3wfdbxm"/><path class="kf07rv5bl"/><path class="q2nszrion"/><path class="ef2afnbgy"/><path class="oqfv9rb9x"/><path class="yvwbi-etd"/><path class="lmoarbbkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:embassy-duotone-bold" {...props}></Icon>
<style>
:global(.ef2afnbgy) {
  d: path("M4 21V10h16v11");
}

:global(.kf07rv5bl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 2v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmoarbbkf) {
  d: path("M12 3h7v4h-7");
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.q2nszrion) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3h7v4h-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t-2qmb_5w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 21V10h16v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tp3wfdbxm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yvwbi-etd) {
  d: path("M12 2v8");
}

</style>
