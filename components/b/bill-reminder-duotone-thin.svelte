<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7uyqxwtl"/><path class="lezox35rc"/><path class="ddtf72jig"/><path class="ky4omnbla"/><path class="y5k8b5bfa"/><path class="nm1qcabkz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bill-reminder-duotone-thin" {...props}></Icon>
<style>
:global(.b7uyqxwtl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ddtf72jig) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 10h5v4H9");
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

:global(.lezox35rc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nm1qcabkz) {
  d: path("M9 10h5v4H9");
}

:global(.y5k8b5bfa) {
  d: path("M9 9v6");
}

</style>
