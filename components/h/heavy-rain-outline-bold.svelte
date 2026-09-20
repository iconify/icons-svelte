<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c-pcdbceg"/><path class="ykv448byy"/><path class="z6i5xtbsj"/><path class="l2z94vbar"/><path class="qvk3j9bfo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:heavy-rain-outline-bold" {...props}></Icon>
<style>
:global(.c-pcdbceg) {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

:global(.l2z94vbar) {
  d: path("m14 15.5 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

:global(.qvk3j9bfo) {
  d: path("m18 18 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ykv448byy) {
  d: path("M6 15.5 8.5 18a2.5 2.5 0 0 1 -5 0Z");
}

:global(.z6i5xtbsj) {
  d: path("m10 18 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

</style>
