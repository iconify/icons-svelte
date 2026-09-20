<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y76hd_85j"/><path class="s--3ooryn"/><path class="npmqe87_t"/><path class="oh0y82bky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:edge-function-outline-regular" {...props}></Icon>
<style>
:global(.npmqe87_t) {
  d: path("m18 8 -2 2v4l2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oh0y82bky) {
  d: path("m20 8 2 2v4l-2 2");
}

:global(.s--3ooryn) {
  d: path("M11 12h4");
}

:global(.y76hd_85j) {
  d: path("M2 6a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
