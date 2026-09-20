<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o-4bk_b4n"/><path class="zkgvk4bog"/><path class="f59axuhhu"/><path class="ldfbmybql"/><path class="z9ittvbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:noon-sun-outline-bold" {...props}></Icon>
<style>
:global(.f59axuhhu) {
  d: path("M4.5 4.5 7 7");
}

:global(.ldfbmybql) {
  d: path("M19.5 4.5 17 7");
}

:global(.o-4bk_b4n) {
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

:global(.zkgvk4bog) {
  d: path("M12 2v3");
}

</style>
