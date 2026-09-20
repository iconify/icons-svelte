<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="axwkrzbmo"/><path class="nuz6-76is"/><path class="zl61012kd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:decoder-only-outline-regular" {...props}></Icon>
<style>
:global(.axwkrzbmo) {
  d: path("m8 8 4 4 -4 4 -4 -4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nuz6-76is) {
  d: path("M15 12h6");
}

:global(.zl61012kd) {
  d: path("M18.5 9.5 21 12l-2.5 2.5");
}

</style>
