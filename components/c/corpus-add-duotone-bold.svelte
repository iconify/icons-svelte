<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rdlk7zbpa"/><path class="xcmc2wqaf"/><path class="na6unfbgc"/><path class="d9hmx-vtp"/><path class="i5d2grbwo"/><path class="s27ukbqxc"/><path class="jls6b8fnh"/><path class="l9kfpmzgx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corpus-add-duotone-bold" {...props}></Icon>
<style>
:global(.d9hmx-vtp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 2v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i5d2grbwo) {
  d: path("M13 2H6v14h10V5");
}

:global(.jls6b8fnh) {
  d: path("M16.5 4.5h5");
}

:global(.l9kfpmzgx) {
  d: path("M19 2v5");
}

:global(.na6unfbgc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 4.5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rdlk7zbpa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 2H6v14h10V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s27ukbqxc) {
  d: path("M16 8H9v14h10V11");
}

:global(.xcmc2wqaf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 8H9v14h10V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
