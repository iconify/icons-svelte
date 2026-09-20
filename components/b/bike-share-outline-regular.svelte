<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jwgl0nbvm"/><path class="erfjsdmyp"/><path class="o178hubwo"/><path class="wcu0lhc9k"/><path class="eaabexbql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bike-share-outline-regular" {...props}></Icon>
<style>
:global(.eaabexbql) {
  d: path("M3 6v13");
}

:global(.erfjsdmyp) {
  d: path("M13.5 15a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

:global(.jwgl0nbvm) {
  d: path("M3.5 15a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o178hubwo) {
  d: path("m7 15 3 -3h4l3 3");
}

:global(.wcu0lhc9k) {
  d: path("M10 8v4");
}

</style>
