<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ufsuvdbvd"/><path class="t1w4rp34a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:club-sandwich" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t1w4rp34a) {
  d: path("m3.75 18.25l2.75-1.5l2.75 1.5l2.75-1.5l2.75 1.5l2.75-1.5l2.75 1.5");
}

:global(.ufsuvdbvd) {
  d: path("M5.75 21.25h12.5a2 2 0 0 0 2-2v-5.6a1 1 0 0 0-.5-.87L5.25 4.45a1 1 0 0 0-1.5.87v13.93a2 2 0 0 0 2 2m-2-7h16.5");
}

</style>
