<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="t_4-59y1e"/><path class="df1wt6xxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dungeon-door" {...props}></Icon>
<style>
:global(.df1wt6xxy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 17.75h.01");
}

:global(.t_4-59y1e) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 21.25V11a7.25 7.25 0 0 1 14.5 0v10.25ZM10.5 7v4.5m3-4.5v4.5m-8.75 2.75h14.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
