<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sa23nmb2h"/><path class="duk1j2buq"/><path class="cdoaxw3fk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:calendar-repeat" {...props}></Icon>
<style>
:global(.cdoaxw3fk) {
  d: path("m8 16.5l1.25-1.25l1.25 1.25");
}

:global(.duk1j2buq) {
  d: path("M12 12.5a2.75 2.75 0 1 1-2.75 2.75");
}

:global(.sa23nmb2h) {
  d: path("M3.5 5h17v15.5h-17ZM8 3v4m8-4v4M3.5 10h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
