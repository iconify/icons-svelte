<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gaxxldbhh"/><path class="tcotthakx"/><path class="shg3wqbxb"/><path class="d251mrbie"/><path class="ukjt4fb6s"/><path class="o035hszqc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-driven-duotone-regular" {...props}></Icon>
<style>
:global(.d251mrbie) {
  d: path("m16 3 -5 5h3l-5 5");
}

:global(.gaxxldbhh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 3 -5 5h3l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o035hszqc) {
  d: path("m14 14 3 3 -3 3");
}

:global(.shg3wqbxb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 14 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tcotthakx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ukjt4fb6s) {
  d: path("M3 17h12");
}

</style>
