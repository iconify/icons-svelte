<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kzvibbczt"/><path class="s2ztwmbwx"/><path class="np1ml0bov"/><path class="pmfm1jbel"/><path class="z5jtjknvm"/><path class="bj2hlhbfp"/><path class="w03o55b0h"/><path class="ds_qvubnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:concurrency-limit-duotone-thin" {...props}></Icon>
<style>
:global(.bj2hlhbfp) {
  d: path("M3 12h12");
}

:global(.ds_qvubnl) {
  d: path("M19 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kzvibbczt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.np1ml0bov) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pmfm1jbel) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s2ztwmbwx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w03o55b0h) {
  d: path("M3 19h12");
}

:global(.z5jtjknvm) {
  d: path("M3 5h12");
}

</style>
