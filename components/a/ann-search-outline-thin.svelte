<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s7h04rdua"/><path class="qxwxnhbhy"/><path class="f1fh1abte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ann-search-outline-thin" {...props}></Icon>
<style>
:global(.f1fh1abte) {
  d: path("m13 20.5 3 -3 3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qxwxnhbhy) {
  d: path("M12.5 12.5 16 16");
}

:global(.s7h04rdua) {
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 1 0 4 9");
}

</style>
