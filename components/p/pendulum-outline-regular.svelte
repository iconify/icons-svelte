<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nktjbrhkd"/><path class="vt7vyubju"/><path class="rxj7i8-nj"/><path class="sy6d_ccqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pendulum-outline-regular" {...props}></Icon>
<style>
:global(.nktjbrhkd) {
  d: path("M4 4h16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rxj7i8-nj) {
  d: path("M9 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.sy6d_ccqn) {
  d: path("M19 16.12a14 14 0 0 1 -14 0");
}

:global(.vt7vyubju) {
  d: path("M12 4v11");
}

</style>
