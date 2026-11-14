<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="siow1dbas"/><path class="h18_52b9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:employee-survey" {...props}></Icon>
<style>
:global(.h18_52b9b) {
  d: path("M9.449 11.625a2.25 2.25 0 0 1-3.898 0M15.25 7.75h.01m2.99 0h.01m-3.459 5.625a2.25 2.25 0 0 1 3.898 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.siow1dbas) {
  d: path("M4.5 3h15a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H10l-4 3.5V17H4.5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2M12 6v8M6 7.75h.01m2.99 0h.01");
}

</style>
