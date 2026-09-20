<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fqboz3btt"/><path class="tgy6cdcqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:action-duotone-bold" {...props}></Icon>
<style>
:global(.fqboz3btt) {
  fill: currentColor;
  d: path("m8 3 9 9 -9 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tgy6cdcqx) {
  d: path("m8 3 9 9 -9 9Z");
}

</style>
