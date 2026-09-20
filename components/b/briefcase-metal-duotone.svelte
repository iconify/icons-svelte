<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="nw01mac5h"/><path class="t1t5zunvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:briefcase-metal-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nw01mac5h) {
  d: path("M224 72v32H32V72a8 8 0 0 1 8-8h176a8 8 0 0 1 8 8M32 200a8 8 0 0 0 8 8h176a8 8 0 0 0 8-8v-32H32Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t1t5zunvh) {
  d: path("M216 56h-40v-8a24 24 0 0 0-24-24h-48a24 24 0 0 0-24 24v8H40a16 16 0 0 0-16 16v128a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V72a16 16 0 0 0-16-16M40 112h176v48H40Zm56-64a8 8 0 0 1 8-8h48a8 8 0 0 1 8 8v8H96Zm120 24v24H40V72Zm0 128H40v-24h176z");
}

</style>
