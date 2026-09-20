<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lbo6t0_1b"/><path class="di40i1kbs"/><path class="uw099db1h"/><path class="b8r0azjjj"/><path class="p0digsbcj"/><path class="pga6n1bci"/><path class="dp6dvchmk"/><path class="p86p59b-c"/><path class="r7xk8o29f"/><path class="h7eeppe6g"/><path class="gkowgccsl"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:histogram-duotone-regular" {...props}></Icon>
<style>
:global(.b8r0azjjj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 9v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.di40i1kbs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dp6dvchmk) {
  d: path("M4 12v8");
}

:global(.gkowgccsl) {
  d: path("M20 14v6");
}

:global(.h7eeppe6g) {
  d: path("M16 9v11");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.lbo6t0_1b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p0digsbcj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p86p59b-c) {
  d: path("M8 7v13");
}

:global(.pga6n1bci) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.uw099db1h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
