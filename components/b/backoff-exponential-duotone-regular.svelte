<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c_xbbkb0k"/><path class="j3gnacbje"/><path class="smcfdu4zn"/><path class="kfyfc0bjf"/><path class="wfd9yacqd"/><path class="fem_64cmj"/><path class="z6x67ktzg"/><path class="xubfi0bjs"/><path class="bnhdslb0j"/><path class="ic_pehd5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backoff-exponential-duotone-regular" {...props}></Icon>
<style>
:global(.bnhdslb0j) {
  d: path("M19 8v6");
}

:global(.c_xbbkb0k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fem_64cmj) {
  d: path("M3 8v6");
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.j3gnacbje) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kfyfc0bjf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.smcfdu4zn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wfd9yacqd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xubfi0bjs) {
  d: path("M11 8v6");
}

:global(.z6x67ktzg) {
  d: path("M6 8v6");
}

</style>
