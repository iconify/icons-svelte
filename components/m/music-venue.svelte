<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="clnd7jbpg"/><path class="g3uxjkbri"/><path class="nh1tkhicc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:music-venue" {...props}></Icon>
<style>
:global(.clnd7jbpg) {
  d: path("m4.456 8.712l5.875-4.838a2.625 2.625 0 0 1 3.338 0l5.875 4.838a2.63 2.63 0 0 1 .956 2.027v7.636A2.625 2.625 0 0 1 17.875 21H6.125A2.625 2.625 0 0 1 3.5 18.375v-7.636a2.63 2.63 0 0 1 .956-2.027");
}

:global(.g3uxjkbri) {
  fill: currentColor;
  d: path("M8.5 16.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nh1tkhicc) {
  d: path("M12 16.5v-7m0 0l3.5 2");
}

</style>
