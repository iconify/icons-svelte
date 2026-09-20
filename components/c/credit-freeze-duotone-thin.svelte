<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7uyqxwtl"/><path class="cul7o--xt"/><path class="audnd8o-u"/><path class="ky4omnbla"/><path class="c1si20bso"/><path class="wihdixnjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:credit-freeze-duotone-thin" {...props}></Icon>
<style>
:global(.audnd8o-u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b7uyqxwtl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c1si20bso) {
  d: path("M10 9v6");
}

:global(.cul7o--xt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ky4omnbla) {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

:global(.wihdixnjz) {
  d: path("M14 9v6");
}

</style>
