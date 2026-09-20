<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wmtj7ubjb"/><path class="bw1nw8b2t"/><path class="wrji4lgnj"/><path class="n3ywj3bst"/><path class="ogegmpq7i"/><path class="kkf3gcbkp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:day-high-outline-regular" {...props}></Icon>
<style>
:global(.bw1nw8b2t) {
  d: path("M10 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.kkf3gcbkp) {
  d: path("M3 20h3");
}

:global(.n3ywj3bst) {
  d: path("M19 7v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ogegmpq7i) {
  d: path("M16.5 9.5 19 7l2.5 2.5");
}

:global(.wmtj7ubjb) {
  d: path("M9.5 15V6a2.5 2.5 0 0 1 5 0v9a4.5 4.5 0 1 1 -5 0");
}

:global(.wrji4lgnj) {
  d: path("M12 8v7");
}

</style>
