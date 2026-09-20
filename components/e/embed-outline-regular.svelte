<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nzpsuduik"/><path class="vhnbtvbtn"/><path class="icg46ikti"/><path class="vshgwuurx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:embed-outline-regular" {...props}></Icon>
<style>
:global(.icg46ikti) {
  d: path("M9.5 12 7 14.5 9.5 17");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.vshgwuurx) {
  d: path("m14.5 12 2.5 2.5 -2.5 2.5");
}

</style>
