<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hk-7c0bfl"/><path class="q-_bdy35o"/><path class="l3yq_fbub"/><path class="euvekjzkt"/><path class="ttx6bbv4v"/><path class="fem_64cmj"/><path class="z6x67ktzg"/><path class="xubfi0bjs"/><path class="bnhdslb0j"/><path class="ic_pehd5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backoff-exponential-duotone-thin" {...props}></Icon>
<style>
:global(.bnhdslb0j) {
  d: path("M19 8v6");
}

:global(.euvekjzkt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fem_64cmj) {
  d: path("M3 8v6");
}

:global(.hk-7c0bfl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.l3yq_fbub) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q-_bdy35o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ttx6bbv4v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
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
