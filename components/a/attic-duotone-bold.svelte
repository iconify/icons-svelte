<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7dovcc6h"/><path class="ccfz103ff"/><path class="b2n5wjbvh"/><path class="o1dsref5n"/><path class="ae0h5kb0o"/><path class="x3sflacnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:attic-duotone-bold" {...props}></Icon>
<style>
:global(.ae0h5kb0o) {
  d: path("M9 15h6");
}

:global(.b2n5wjbvh) {
  d: path("M9 12v9");
}

:global(.ccfz103ff) {
  d: path("M2 12 12 2l10 10Z");
}

:global(.h7dovcc6h) {
  fill: currentColor;
  d: path("M2 12 12 2l10 10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o1dsref5n) {
  d: path("M15 12v9");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x3sflacnk) {
  d: path("M9 18h6");
}

</style>
