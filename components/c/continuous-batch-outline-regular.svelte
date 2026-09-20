<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sfn7tmb6c"/><path class="t_-p3gl9a"/><path class="zg6lybc6r"/><path class="h3f_66bxu"/><path class="i3md2ibef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:continuous-batch-outline-regular" {...props}></Icon>
<style>
:global(.h3f_66bxu) {
  d: path("M14 12h5a3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3v-3l3 -3h5");
}

:global(.i3md2ibef) {
  d: path("M5 16.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sfn7tmb6c) {
  d: path("M4 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.t_-p3gl9a) {
  d: path("M8 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zg6lybc6r) {
  d: path("M12 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
