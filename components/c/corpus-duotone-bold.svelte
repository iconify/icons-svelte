<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rdlk7zbpa"/><path class="xcmc2wqaf"/><path class="i5d2grbwo"/><path class="s27ukbqxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corpus-duotone-bold" {...props}></Icon>
<style>
:global(.i5d2grbwo) {
  d: path("M13 2H6v14h10V5");
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
