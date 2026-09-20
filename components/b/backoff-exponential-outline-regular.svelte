<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fem_64cmj"/><path class="z6x67ktzg"/><path class="xubfi0bjs"/><path class="bnhdslb0j"/><path class="ic_pehd5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backoff-exponential-outline-regular" {...props}></Icon>
<style>
:global(.bnhdslb0j) {
  d: path("M19 8v6");
}

:global(.fem_64cmj) {
  d: path("M3 8v6");
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xubfi0bjs) {
  d: path("M11 8v6");
}

:global(.z6x67ktzg) {
  d: path("M6 8v6");
}

</style>
