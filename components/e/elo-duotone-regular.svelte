<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l6baspbie"/><path class="pldekmw0i"/><path class="ns53blbaz"/><path class="pj7pdobto"/><path class="hm90u5bqs"/><path class="pb1wrt76j"/><path class="bt2nqn0-a"/><path class="a-jefodqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:elo-duotone-regular" {...props}></Icon>
<style>
:global(.a-jefodqm) {
  d: path("M15.5 17.5 18 20l2.5 -2.5");
}

:global(.bt2nqn0-a) {
  d: path("M18 11v9");
}

:global(.hm90u5bqs) {
  d: path("M3.5 6.5 6 4l2.5 2.5");
}

:global(.l6baspbie) {
  fill: currentColor;
  d: path("M3 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ns53blbaz) {
  d: path("M3 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.pb1wrt76j) {
  d: path("M15 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.pj7pdobto) {
  d: path("M6 4v9");
}

:global(.pldekmw0i) {
  fill: currentColor;
  d: path("M15 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
