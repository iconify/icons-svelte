<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nl-hnlp7a"/><path class="p8-4n3b5e"/><path class="wj8ybccjk"/><path class="f1t8iyb4a"/><path class="y_lfs3-op"/><path class="hsnj9o-9y"/><path class="dp6dvchmk"/><path class="p86p59b-c"/><path class="r7xk8o29f"/><path class="h7eeppe6g"/><path class="gkowgccsl"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:histogram-duotone-thin" {...props}></Icon>
<style>
:global(.dp6dvchmk) {
  d: path("M4 12v8");
}

:global(.f1t8iyb4a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 9v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gkowgccsl) {
  d: path("M20 14v6");
}

:global(.h7eeppe6g) {
  d: path("M16 9v11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsnj9o-9y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.nl-hnlp7a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p8-4n3b5e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p86p59b-c) {
  d: path("M8 7v13");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.wj8ybccjk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y_lfs3-op) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
