<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lsmbw6b7c"/><path class="ni-y6nb3x"/><path class="un16mhhsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:private-room" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lsmbw6b7c) {
  d: path("M4 21.5v-17c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2v2.681M2.5 21.5h19");
}

:global(.ni-y6nb3x) {
  d: path("M13.5 11v6.5c0 .55.45 1 1 1h5c.55 0 1-.45 1-1V11c0-.55-.45-1-1-1h-5c-.55 0-1 .45-1 1");
}

:global(.un16mhhsx) {
  d: path("M16 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0m-.75 3.5h3.5");
}

</style>
