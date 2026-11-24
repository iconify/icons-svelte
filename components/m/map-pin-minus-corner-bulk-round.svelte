<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ooj7xybof"/><path class="vd13vixwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-pin-minus-corner-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ooj7xybof) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.567 17.929l.423 2.928a1.001 1.001 0 0 1-1.545.975c-1.854-1.237-3.557-2.817-4.876-4.616a14 14 0 0 1-1.832-3.314A10.9 10.9 0 0 1 2 10a7.98 7.98 0 0 1 2.343-5.657A8.002 8.002 0 0 1 17.98 9.43a1 1 0 0 1-.995 1.07a6.492 6.492 0 0 0-6.418 7.429");
}

:global(.vd13vixwi) {
  d: path("M7.236 7.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414M21 15a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

</style>
