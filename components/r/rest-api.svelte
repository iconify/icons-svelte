<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zol1zbbql"/><path class="mwmw3htlu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rest-api" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mwmw3htlu) {
  d: path("M7 17.25v3a5 1.25 0 0 0 10 0v-3M12 9v4.25M9.75 11L12 13.25L14.25 11");
}

:global(.zol1zbbql) {
  d: path("M8.5 9a2.5 2.5 0 0 1 0-5a3.75 3.75 0 0 1 6.75.5a2.25 2.25 0 0 1 0 4.5ZM7 17.25a5 1.25 0 1 0 10 0a5 1.25 0 1 0-10 0");
}

</style>
