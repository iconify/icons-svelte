<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ht1vpzu4f"/><path class="hr42q26km"/><path class="i8njtcg0g"/><path class="od43g3bud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cleanser-tube-sharp" {...props}></Icon>
<style>
:global(.hr42q26km) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.25 9.75a1.5 1.5 0 1 1-3 0a1.5 1.5 0 1 1 3 0");
}

:global(.ht1vpzu4f) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.75h11.5l-.15.99l-1.45 9.27l-.15.99l-.8.6l-.4.3l-.8.6h-5l-.8-.6l-.4-.3l-.8-.6l-.15-.99L5.9 3.74l-.15-.99zm-.5 2.5h11.5");
}

:global(.i8njtcg0g) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 12.5h.01");
}

:global(.od43g3bud) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 18.5h7v2.75h-7z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
