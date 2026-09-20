<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gtlfk7rgu"/><path class="b5ic9acln"/><path class="skjwr0c_z"/><path class="xtpdjx99u"/><path class="de8hz-_3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:colbert-duotone-thin" {...props}></Icon>
<style>
:global(.b5ic9acln) {
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
}

:global(.de8hz-_3f) {
  d: path("M15 10.5v5");
}

:global(.gtlfk7rgu) {
  fill: currentColor;
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.skjwr0c_z) {
  d: path("M9 10.5v5");
}

:global(.xtpdjx99u) {
  d: path("M12 10.5v5");
}

</style>
