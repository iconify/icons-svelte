<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g91uwsb-i"/><path class="vh7n7xb8n"/><path class="y18tiu7ut"/><path class="ygzwcphiv"/><path class="cjsg0ab2y"/><path class="fjkpt106v"/><path class="b9coo-b0i"/><path class="i7tgsrb7i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:beaufort-duotone-bold" {...props}></Icon>
<style>
:global(.b9coo-b0i) {
  d: path("M10.5 20v-9h5v9");
}

:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.fjkpt106v) {
  d: path("M3 20v-5h5v5");
}

:global(.g91uwsb-i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i7tgsrb7i) {
  d: path("M18 20V6h3v14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vh7n7xb8n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20v-5h5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y18tiu7ut) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10.5 20v-9h5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ygzwcphiv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 20V6h3v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
