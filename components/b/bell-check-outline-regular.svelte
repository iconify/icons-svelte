<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="srzgk7jml"/><path class="jkuojibnm"/><path class="jdqylbbkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bell-check-outline-regular" {...props}></Icon>
<style>
:global(.jdqylbbkf) {
  d: path("m9 14 2 2 4 -4");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.srzgk7jml) {
  d: path("M3 17a9 9 0 0 1 18 0");
}

</style>
