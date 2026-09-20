<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6t30nbxd"/><path class="k0l21tbkp"/><path class="kr5tlbbsn"/><path class="xrnoeq00r"/><path class="bj2hlhbfp"/><path class="ic_pehd5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rollout-duotone-bold" {...props}></Icon>
<style>
:global(.bj2hlhbfp) {
  d: path("M3 12h12");
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.k0l21tbkp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k6t30nbxd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kr5tlbbsn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xrnoeq00r) {
  d: path("M3 7h6");
}

</style>
