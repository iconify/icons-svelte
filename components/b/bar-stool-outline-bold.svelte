<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k4qo1xe9v"/><path class="hu2mwjewo"/><path class="l46p6bckm"/><path class="zka_zabrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bar-stool-outline-bold" {...props}></Icon>
<style>
:global(.hu2mwjewo) {
  d: path("M12 6v10");
}

:global(.k4qo1xe9v) {
  d: path("M4 6h16");
}

:global(.l46p6bckm) {
  d: path("m8 20 4 -4 4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zka_zabrc) {
  d: path("M9 13h6");
}

</style>
