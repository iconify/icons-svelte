<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bx6xbv1rh"/><path class="bx28cy56t"/><path class="u3x3u-byr"/><path class="nsdzhhb8h"/><path class="s3lxg1bko"/><path class="jw-230sxh"/><path class="rckmicclj"/><path class="so0bhmbof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hamster-duotone-regular" {...props}></Icon>
<style>
:global(.bx28cy56t) {
  fill: currentColor;
  d: path("M6 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.bx6xbv1rh) {
  fill: currentColor;
  d: path("M12 19c-4 0 -7 -3 -7 -6 0 -4 3 -6 7 -6s7 2 7 6c0 3 -3 6 -7 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jw-230sxh) {
  d: path("M6 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nsdzhhb8h) {
  fill: currentColor;
  d: path("M11 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rckmicclj) {
  d: path("M14 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s3lxg1bko) {
  d: path("M12 19c-4 0 -7 -3 -7 -6 0 -4 3 -6 7 -6s7 2 7 6c0 3 -3 6 -7 6");
}

:global(.so0bhmbof) {
  d: path("M11 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.u3x3u-byr) {
  fill: currentColor;
  d: path("M14 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
