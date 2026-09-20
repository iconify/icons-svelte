<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cpf_19bsz"/><path class="kxg4twbvh"/><path class="n46b5qbde"/><path class="tsqy9joje"/><path class="g3lrzsbos"/><path class="uepsd3bvn"/><path class="q83h1dbic"/><path class="m_5u0ccez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reasoning-trace-duotone-bold" {...props}></Icon>
<style>
:global(.cpf_19bsz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g3lrzsbos) {
  d: path("M3 5h7");
}

:global(.kxg4twbvh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 10h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m_5u0ccez) {
  d: path("M15 20h7");
}

:global(.n46b5qbde) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 15h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q83h1dbic) {
  d: path("M11 15h7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tsqy9joje) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 20h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uepsd3bvn) {
  d: path("M7 10h7");
}

</style>
