<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fphosebtn"/><path class="s6ndlwbpa"/><path class="qdk1t7u-k"/><path class="l8xl8ub_k"/><path class="kr5tlbbsn"/><path class="fem_64cmj"/><path class="z6x67ktzg"/><path class="xubfi0bjs"/><path class="bnhdslb0j"/><path class="ic_pehd5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backoff-exponential-duotone-bold" {...props}></Icon>
<style>
:global(.bnhdslb0j) {
  d: path("M19 8v6");
}

:global(.fem_64cmj) {
  d: path("M3 8v6");
}

:global(.fphosebtn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.kr5tlbbsn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l8xl8ub_k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qdk1t7u-k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s6ndlwbpa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xubfi0bjs) {
  d: path("M11 8v6");
}

:global(.z6x67ktzg) {
  d: path("M6 8v6");
}

</style>
