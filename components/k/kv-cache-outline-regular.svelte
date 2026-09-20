<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="okud9xj_d"/><path class="t6hm3zb9t"/><path class="qowfo405a"/><path class="cisx0soqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:kv-cache-outline-regular" {...props}></Icon>
<style>
:global(.cisx0soqo) {
  d: path("M12 15h7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.okud9xj_d) {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.qowfo405a) {
  d: path("M12 9h7");
}

:global(.t6hm3zb9t) {
  d: path("M10 5v14");
}

</style>
