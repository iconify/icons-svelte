<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x25fue1gb"/><path class="j9-ez86da"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:publisher-person" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j9-ez86da) {
  d: path("M12 17q-1.125-1.125-3-.75v4q1.875-.375 3 .75q1.125-1.125 3-.75v-4q-1.875-.375-3 .75m0 0v4");
}

:global(.x25fue1gb) {
  d: path("M8.5 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M4 21.5c0-5 3.5-8.5 8-8.5s8 3.5 8 8.5");
}

</style>
