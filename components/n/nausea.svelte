<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="twmh6dblz"/><path class="m27crlb1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:nausea" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m27crlb1n) {
  d: path("M12 10a1 1 0 0 0-2 0a2.25 2.25 0 0 0 4.5 0a3.5 3.5 0 0 0-7 0");
}

:global(.twmh6dblz) {
  d: path("M15.75 21.25v-3h1.75a1.5 1.5 0 0 0 1.5-1.5v-2.5l1.5-.5c.5-.2.6-.7.3-1.1L19 10c-.25-4.25-3.25-7.25-7.5-7.25C7 2.75 3.75 6 3.75 10.5c0 2.6 1.1 4.5 3 6v4.75Z");
}

</style>
