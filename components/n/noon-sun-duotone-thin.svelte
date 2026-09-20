<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xnrghp1vk"/><path class="o-4bk_b4n"/><path class="zkgvk4bog"/><path class="f59axuhhu"/><path class="ldfbmybql"/><path class="z9ittvbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:noon-sun-duotone-thin" {...props}></Icon>
<style>
:global(.f59axuhhu) {
  d: path("M4.5 4.5 7 7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ldfbmybql) {
  d: path("M19.5 4.5 17 7");
}

:global(.o-4bk_b4n) {
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
}

:global(.xnrghp1vk) {
  fill: currentColor;
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

:global(.zkgvk4bog) {
  d: path("M12 2v3");
}

</style>
