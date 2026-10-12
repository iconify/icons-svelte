<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="phpyl6g6f"/><path class="hlskcib9f"/><path class="cbrcj8fol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:landslide-sharp" {...props}></Icon>
<style>
:global(.cbrcj8fol) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.5 15.25h.01");
}

:global(.hlskcib9f) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 11.5l4.25.75l3 4.5m7.34-8.85l1.82-.3l.59-.1l.21.56l.58 1.63l.21.56l-.53.29l-1.69.92l-.53.29l-.19-.57l-.87-2.61l-.19-.57z");
}

:global(.phpyl6g6f) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.05V4.75H7.5l.77.92l12.21 14.66l.77.92H2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
